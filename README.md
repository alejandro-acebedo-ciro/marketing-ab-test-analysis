# Marketing A/B Test Analysis

Analysis of a public A/B test (588,101 users) comparing an advertisement with a neutral public service announcement (PSA). I analyzed the completed experiment; I did not run it.

**Key findings**
- The ad group converted at 2.55% vs. 1.79% for the PSA group: a lift of 0.77 percentage points (95% CI: 0.60 to 0.94; p < 0.001), about 7.7 extra sales per 1,000 users.
- Break-even profit-per-sale thresholds are computed across hypothetical ad-cost scenarios.
- Conversion rises with exposure in both groups, so ad frequency should not be read as causal.

**Files:** `ab_test_analysis.ipynb` (full analysis)

**Data:** [Kaggle: Marketing A/B Testing](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing). Download `marketing_AB.csv` and place it next to the notebook to reproduce.

**Tools:** Python, pandas, statsmodels, matplotlib
