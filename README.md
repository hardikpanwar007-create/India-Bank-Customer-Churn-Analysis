# IndiaBank Customer Analytics Dashboard

---

## Project Overview

Analyzed 10,000 real bank customers to uncover sales performance trends, segment customers by value, and predict churn risk. This project performs a full-cycle customer analytics study on a retail banking dataset, mirroring real-world business analyst workflows used at banks like **HDFC, ICICI, and Axis Bank.**


---

## Business Problem

The bank's leadership team identified three critical concerns:
- **Revenue concentration risk** - over-reliance on certain geographies and product segments
- **Rising customer attrition** - churn rate exceeding industry benchmarks
- **No predictive capability** - no early warning system for at-risk customers

---

## Dashboard Preview

### Page 1 - Sales & Revenue Performance
### Page 2 - Customer Segmentation
### Page 3 - Churn Risk Analysis

---

## Dataset Overview

**Source:** [Bank Customer Churn Dataset — Kaggle](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)

| Total Records | 10,000 customers |
| Total Features | 18 original + 6 engineered |
| Geography | France, Germany, Spain |


### Engineered Features (Added in Excel)

| `Age_Group` | Bucketed into 18-30, 31-45, 46-60, 60+ |
| `Balance_Segment` | High / Medium / Low / Zero Balance |
| `Customer_Score` | Weighted score out of 100 |
| `Churn_Risk_Score` | Custom weighted scoring model out of 150 |
| `Churn_Risk` | High Risk / Medium Risk / Low Risk |
| `Revenue_Tier` | HNI / Preferred / Classic / Basic |

---

## Key Insights

### 1. Sales & Revenue
- **Germany** has the highest average balance but also the highest churn rate
- **HNI segment** holds 4x more balance than Basic tier customers

### 2. Customer Segmentation
- **Diamond card** holders have the highest average points earned
- **31-45 age group** holds the highest average balance
- **Inactive members** represent the biggest churn risk

### 3. Churn Analysis
- **Overall churn rate: 20.4%**
- **High Risk customers churn at 55%** — 2.7x the overall rate
- **Low Risk customers churn at just 1.6%** — validating the model
- **Germany** has the highest churn rate across all risk tiers
- **Satisfaction Score 1** customers churn at nearly 3x the average

---


**## Churn Risk Scoring Model**

Custom rule-based scoring model built in Excel:

| Complained | 30 |
| Inactive Member | 30 |
| Low Satisfaction (1-2) | Up to 30 |
| Low Balance Segment | Up to 15 |
| Few Products | 10 |
| Short Tenure (≤3 yrs) | 20 |
| Poor Credit Score | Up to 15 |
| **Max Score** | **150** |
| ≥ 90 | High Risk | 55% |
| 50 – 89 | Medium Risk | 13.6% |
| < 50 | Low Risk | 1.6% |

**Model Lift: 2.7x** - High Risk customers are 2.7x more likely to churn

---

## Business Recommendations

1. **Immediate:** Launch retention campaign for 2,310 High Risk customers - prioritise Germany
2. **Short term:** Improve satisfaction scores - customers rating 1-2 churn at 3x average
3. **Long term:** Develop loyalty program for Basic tier - highest churn segment overall

---


## Author

**Hardik Parmar**
[LinkedIn](https://www.linkedin.com/in/hardiksinghparmar) · [GitHub](https://github.com/hardikpanwar007-create)
