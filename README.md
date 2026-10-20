# SkillCraft Technology – Task 4: Business Insights Report (EDA)

## Project Overview

This project was completed as part of the Data Analyst Internship at SkillCraft Technology.

The objective was to perform Exploratory Data Analysis (EDA) on a marketing campaign dataset, analyze the conversion funnel, compare marketing channel performance, and recommend budget allocation based on Return on Investment (ROI).

## Dataset

- Dataset: Sample Marketing Campaign Dataset
- Original records: 260
- Original columns: 8
- Marketing channels: 7

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Google Colab

## Data Cleaning and Preparation

- Loaded and explored the marketing campaign dataset.
- Checked for missing values; none were found.
- Checked for duplicate rows; none were found.
- Converted the date column from object to datetime format.
- Calculated additional marketing performance metrics.

## Key Performance Metrics

- Click-Through Rate (CTR)
- Conversion Rate
- Cost Per Click (CPC)
- Return on Investment (ROI)

ROI was calculated using the following formula:

ROI (%) = ((Revenue - Marketing Spend) / Marketing Spend) × 100

## Conversion Funnel Analysis

The conversion funnel summarizes the following results:

- Total Impressions: 11,624,555
- Total Clicks: 394,168
- Total Conversions: 25,422
- Click-Through Rate: 3.39%
- Conversion Rate from Clicks: 6.45%
- Overall Conversion Rate: 0.22%

## ROI by Marketing Channel

| Marketing Channel | ROI (%) |
|---|---:|
| Meta Ads | 531.31 |
| LinkedIn | 417.88 |
| Affiliate | 371.55 |
| Organic | 283.91 |
| Email | 265.40 |
| Google Ads | 256.63 |
| TikTok | 240.32 |

## Key Business Insights

- Meta Ads achieved the highest ROI at 531.31%.
- LinkedIn ranked second with an ROI of 417.88%.
- Affiliate marketing ranked third with an ROI of 371.55%.
- TikTok had the lowest ROI among the seven channels at 240.32%.
- All seven channels showed positive ROI under the calculation used.

## Budget Recommendations

- Prioritize controlled budget increases for Meta Ads and LinkedIn.
- Consider Affiliate as the next channel for expansion testing.
- Continue monitoring Organic, Email, and Google Ads for optimization opportunities.
- Optimize TikTok campaigns and evaluate their performance before making major budget reductions.
- Monitor ROI, conversion rates, and cost per conversion before scaling marketing spend.

## Project Files

- `SkillCraft_Task_4_Business_Insights_EDA.ipynb` – Notebook containing the analysis, calculations, visualizations, and report.
- `Marketing_Campaign_Cleaned.csv` – Cleaned dataset with calculated marketing metrics.
- `Marketing_Conversion_Funnel.png` – Conversion funnel visualization
