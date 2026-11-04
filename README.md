# South Africa vs Australia — Why South Africa Won

A Power BI cricket analytics case study using ball-by-ball delivery data to explain South Africa's innings victory.

## Match result

- **Fixture:** South Africa vs Australia
- **Format:** Test
- **Venue:** St George's Park, Gqeberha
- **Dates in supplied dataset:** 18–22 October 2026
- **Result:** South Africa won by an innings and 31 runs
- **Scores:** South Africa 425/9 declared; Australia 99 all out and 295 all out

## The short match analysis

South Africa's first-innings 425/9 declaration created the decisive advantage. T Bavuma led with 179, supported by M Jansen (85) and SR Harmer (82), giving South Africa a substantial total rather than relying on a single innings contribution.

Australia were dismissed for 99 in the first innings, scoring at 2.32 runs per over. Their dot-ball rate was 79.7%, the highest of the three innings in the supplied data. South Africa's bowlers repeatedly denied scoring opportunities and took wickets at regular intervals.

Australia showed more resistance in the second innings, reaching 295, with TM Head scoring 121. However, the innings still had a 74.3% dot-ball rate and a scoring rate of 2.74 runs per over. Australia made 394 across both innings (99 + 295), which remained 31 runs short of South Africa's first-innings total of 425. That is why the result was an innings victory.

## Evidence from the charts

- **Innings comparison:** 425/9d vs 99 all out vs 295 all out.
- **Batting contributions:** T Bavuma 179, M Jansen 85, SR Harmer 82; Australia's leading second-innings scorer was TM Head with 121.
- **Dot-ball rates:** South Africa 70.2%; Australia first innings 79.7%; Australia second innings 74.3%.
- **Bowling contribution across Australia's two innings:** M Jansen 6 wickets, K Rabada 6, P W A Mulder 5, SR Harmer 2 and A Nortje 1.

## Dashboard pages

1. **Match overview:** innings score comparison and dot-ball pressure.
2. **Batting analysis:** leading batter contributions.
3. **Bowling analysis:** bowler-credited wickets across Australia's two innings.

The SVGs in `assets/` are accurate portfolio chart summaries generated from the supplied delivery data. They are not screenshots of the editable Power BI report.

## Tools and skills

Cricsheet YAML, Python data preparation, Power BI Desktop, Power Query, DAX, data cleaning, calculated columns, measures, aggregation and data visualization.

## Data notes

The source YAML was flattened into a delivery-level table. A dot ball is a delivery on which the batting team scores zero total runs, including extras. Bowling wickets count only dismissal types credited to the bowler. Match details and figures are reproduced from the supplied project dataset; this portfolio is not an independently verified real-world match report. The editable Power BI `.pbix` file and original ball-by-ball data are not included in this public repository.
