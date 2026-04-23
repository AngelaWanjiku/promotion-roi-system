Promotion Revenue Optimization & Profitability System
Stack: Python · MySQL · Power BI · Excel

Why I built this
60% of consumer goods companies can't explain why their promotions succeed or fail - and 71% haven't fully used analytics to fix that.
That stat stuck with me. I come from a finance background and the question of which spend actually returns value is something I've seen mishandled at every level. So I built a system to answer it properly, end to end.
This project traces a full analytics pipeline: raw FMCG data > Excel cleaning > Python feature engineering > Power BI executive dashboard. The goal was to identify which promotions drive real profit, which ones quietly destroy margin, and what that means strategically by category and location.

What the system does

Calculates true promotion ROI per transaction - not just sales volume
Engineers profit labels and flags loss-making promotions
Runs K-means clustering to segment transactions by profit behavior
Tests for cross-category association rules during promotional periods
Visualizes everything in a 4-page Power BI executive dashboard


Key findings
InsightDetailHighest ROI combinationSuburban Household promotions at 258% avg ROIWorst performingRural Dairy at 61% avg ROI - 4x below Urban DairyLoss-making promotions17.4% of all promotions ran at a lossCross-category patternsNo significant basket-building detected - promotions drive single-category demandBest rural opportunitySnacks at 207% ROI - high return, likely low competition


Dashboard pages
Page 1 - Executive Sales Overview
KPI cards, promotion vs non-promotion breakdown, revenue by category and promotion status.
Page 2 - Profit & ROI Analysis
Profit breakdown by category and promotion impact, ROI trend over time, promotion impact distribution.
Page 3 - Performance Insights & Strategy
Heatmap of avg promo ROI by category and store location, with data-backed strategic recommendations.
Page 4 - Data Mining & Customer Segmentation
K-means cluster distribution by profit label, association rules analysis and findings.

Tools used
ToolWhat I used it forExcelInitial data cleaning and explorationPython (Pandas)Feature engineering - profit, promo cost, ROI calculationsPython (Scikit-learn)K-means clusteringPython (Mlxtend)Association rules miningMySQLData storage and queryingPower BIExecutive dashboard and visual reporting

A note on the data
Built on a synthetic FMCG dataset, cleaned and engineered to simulate real promotion performance scenarios. ROI figures are directionally illustrative rather than industry-benchmarked. The analytical approach and pipeline structure reflect real-world Revenue Management workflows.
