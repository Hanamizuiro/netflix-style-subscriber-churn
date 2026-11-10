# Netflix-Style Subscriber Churn and Engagement Analysis

<div align="center">
  <a href="https://commons.wikimedia.org/wiki/File:Netflix_2015_logo.svg">
    <img src="https://thumb.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/330px-Netflix_2015_logo.svg.png"
         alt="Netflix logo" width="180">
  </a>
</div>

## Overview

This case study analyses 5,000 streaming subscriber records to identify which plans and engagement patterns a retention team should investigate.

**Tools** · Python, Pandas, Matplotlib, and Seaborn

[Analysis notebook](netflix-churn-engagement.ipynb) · [Dataset on Kaggle](https://www.kaggle.com/datasets/zeyadmohamed26/netflix-customer-churn-and-engagement-analytics)

## Questions and answers

| Question | Finding |
| --- | --- |
| How common was churn? | **50.3%** were labeled as churned (2,515 of 5,000) and 49.7% as retained (2,485). |
| Which plan had the highest churn? | Basic led in both proportion and count at **61.8%** (1,027 of 1,661). Standard was at 45.4% and Premium at 43.7%. |
| How did churn vary by login recency? | Churn ranged from **19.7%** at 0–14 days since last login to **76.0%** at 45 or more days. |
| How did daily watch time differ? | The median was **0.12 hours** for churned subscribers and **0.72 hours** for retained subscribers. Ten records reporting over 24 hours per day were excluded from this comparison. |
| How much did churn vary by region? | Europe had the highest proportion at 51.7% (448 of 867) and Africa the lowest at 48.3% (388 of 803), a gap of **3.4 percentage points**. |
| Which devices had the highest churn within each plan? | Laptop led in Basic (65.7%) and Standard (48.6%). Mobile led in Premium (46.7%). |
| What happened when both engagement signals were present? | Churn was **91.5%** (1,596 of 1,744) for subscribers who watched under 18 minutes per day and last logged in at least 30 days ago, versus **7.0%** (117 of 1,669) for neither signal. |

## Conclusion

Start with Basic and verify whether the engagement signals were recorded before cancellation. The dataset gives no observation dates, so the percentages describe churn labels within the sample.
