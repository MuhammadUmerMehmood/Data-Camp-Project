# 📊 Churn Analysis — Fit.ly Tech

A data analysis project examining customer churn for **Fit.ly Tech**, a subscription-based fitness app. This project was completed as part of the **DataCamp Data Analyst Certification (DA601P)**.

---

## 📁 Project Overview

Over the past two quarters, Fit.ly Tech noticed churn increasing across its subscriber base. This analysis uses data from three sources to identify the key drivers of churn and provide actionable recommendations for leadership.

---

## 📂 Dataset

Three datasets were used:

| Dataset | Rows | Key Columns |
|---|---|---|
| `account_info.csv` | 400 | customer_id, email, state, plan, plan_list_price, churn_status |
| `customer_support.csv` | 918 | ticket_time, user_id, channel, topic, resolution_time_hours |
| `user_activity.csv` | 445 | event_time, user_id, event_type |

---

## 🔍 Key Findings

- **28.5% overall churn rate** — nearly 1 in 3 customers left the platform
- **Free plan has the highest churn at 41%** — well above the average
- **Inactive users churn at 53.9%** — the single biggest churn driver
- **Highly engaged users have 0% churn** — engagement is everything
- **154 out of 400 customers (38.5%) had zero activity**

---

## 📈 Business Metric

**Monthly Churn Rate (MCR)**
> Churned Customers ÷ Total Customers at Start of Period

| Plan | Churn Rate |
|---|---|
| Free | 41.0% |
| Enterprise | 26.1% |
| Basic | 23.7% |
| Pro | 22.4% |

**Target:** Reduce overall churn to below 20% within 2 quarters

---

## 💡 Recommendations

1. **Re-engage inactive users** — trigger automated emails for users inactive 7+ days
2. **Convert Free users to paid plans** — offer limited-time upgrades
3. **Reduce repeat support contacts** — improve onboarding and FAQs
4. **Resolve open tickets faster** — 45% of tickets are currently unresolved
5. **Track MCR monthly** — alert team if any segment exceeds 30%

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- DataCamp DataLab
- PowerPoint (presentation slides)

---

## 👤 Author

**Umer Mehmood**  
DataCamp Data Analyst Certification — Practical Exam DA601P
