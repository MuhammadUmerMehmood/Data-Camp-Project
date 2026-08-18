# Churn Analysis: Fit.ly Tech

A data analysis project examining customer churn for Fit.ly Tech, a subscription-based fitness app. Completed as part of the DataCamp Data Analyst Certification (Practical Exam DA601P).

## Project Overview

Over two recent quarters, Fit.ly Tech saw churn rising across its subscriber base. This analysis draws on three data sources to identify the key drivers of churn and to set out actionable recommendations for leadership.

## Dataset

Three datasets were used:

| Dataset | Rows | Key Columns |
|---|---|---|
| `account_info.csv` | 400 | customer_id, email, state, plan, plan_list_price, churn_status |
| `customer_support.csv` | 918 | ticket_time, user_id, channel, topic, resolution_time_hours |
| `user_activity.csv` | 445 | event_time, user_id, event_type |

## Key Findings

- Overall churn rate of 28.5 percent, meaning nearly 1 in 3 customers left the platform.
- The Free plan has the highest churn at 41 percent, well above the average.
- Inactive users churn at 53.9 percent, the single biggest driver of churn.
- Highly engaged users show 0 percent churn, confirming that engagement is the strongest retention factor.
- 154 of 400 customers (38.5 percent) recorded zero activity.

## Business Metric

The core metric is the Monthly Churn Rate (MCR):

> Churned Customers / Total Customers at Start of Period

| Plan | Churn Rate |
|---|---|
| Free | 41.0% |
| Enterprise | 26.1% |
| Basic | 23.7% |
| Pro | 22.4% |

Target: reduce overall churn to below 20 percent within two quarters.

## Recommendations

1. Re-engage inactive users by triggering automated emails for anyone inactive for 7 or more days.
2. Convert Free users to paid plans through limited-time upgrade offers.
3. Reduce repeat support contacts by improving onboarding and FAQs.
4. Resolve open tickets faster, as 45 percent of tickets are currently unresolved.
5. Track MCR monthly and alert the team if any segment exceeds 30 percent.

## Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- DataCamp DataLab
- PowerPoint (presentation slides)

## Author

**Umer Mehmood**

DataCamp Data Analyst Certification, Practical Exam DA601P
