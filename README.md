# Netflix-Style Subscriber Churn and Engagement Analysis

<a href="https://commons.wikimedia.org/wiki/File:Netflix_2015_logo.svg"><img src="https://thumb.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/330px-Netflix_2015_logo.svg.png" alt="Netflix logo" width="180"></a>

#### Background

This Netflix-style case study covers 5,000 streaming subscribers. The dataset records subscription plans, viewing activity, time since last login, device, region, and whether each subscriber is labeled as churned.

#### Task

Analyse how subscription plans and engagement relate to recorded churn and identify which patterns a retention team should investigate.

#### Questions and Answers

- **How many subscribers were labeled as churned or retained?**

  Of 5,000 subscribers, 2,515 (50.3%) were labeled as churned and 2,485 (49.7%) as retained.

- **Which plan had the highest churn proportion and the most churned subscribers?**

  Basic led on both measures at 61.8% (1,027 of 1,661), followed by Standard at 45.4% (748 of 1,646) and Premium at 43.7% (740 of 1,693).

- **How did churn vary by days since last login?**

  The churn proportion rose from 19.7% at 0–14 days (238 of 1,209) to 76.0% at 45 or more days (996 of 1,311). The largest jump was between 15–29 days (31.6%) and 30–44 days (71.6%).

- **How did daily watch time differ between churned and retained subscribers?**

  Median daily watch time was 0.12 hours for churned subscribers and 0.72 hours for retained subscribers. The comparison excluded 10 records reporting more than 24 hours per day.

- **How large were the differences across regions?**

  Europe had the highest observed proportion at 51.7% (448 of 867) and Africa the lowest at 48.3% (388 of 803), a gap of 3.4 percentage points.

- **Within each subscription plan, which devices had the highest churn proportion?**

  Laptop led in Basic (65.7%, 215 of 327) and Standard (48.6%, 170 of 350). Mobile led in Premium (46.7%, 155 of 332).

- **Was churn more common when both engagement signals were present?**

  Among subscribers who watched under 18 minutes per day and last logged in at least 30 days ago, 91.5% were labeled as churned (1,596 of 1,744). The proportion was 66.7% for low viewing alone, 35.9% for less recent login alone, and 7.0% for neither signal.

The percentages describe churn labels within this dataset. The observation period and timing of engagement relative to cancellation are unverified.

#### Tools

Python and Pandas for data cleaning, transformation, and analysis. Matplotlib and Seaborn for visualisation.

#### Data Set

The source file is publicly available on [Kaggle](https://www.kaggle.com/datasets/zeyadmohamed26/netflix-customer-churn-and-engagement-analytics).

#### Posted in

[GitHub notebook with the answers, charts, and conclusion](netflix-churn-engagement.ipynb)
