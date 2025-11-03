# Business-report-and-data-storytelling-for-collections-strategy task 3
how to apply AI insights in their decision-making.

🧩 Project Overview

This project represents Task 3 of the Geldium Credit Risk Analysis series. Building on the Exploratory Data Analysis (Task 1) and Predictive Modeling Plan (Task 2), this task focuses on translating data-driven insights into actionable business recommendations for improving Geldium’s loan collections strategy.

The analysis leverages the results of delinquency prediction models to identify high-risk customer segments and propose targeted intervention strategies.

🧠 Key Predictive Insights

Based on predictive modeling and EDA findings, the following trends were identified:

High-risk segment: Customers under 30 years old with 2 or more missed payments and credit utilization above 50% are most likely to become delinquent.

Debt-to-Income ratio: A ratio greater than 0.5 correlates strongly with late or missed payments.

Account Tenure: Customers with less than 12 months of tenure demonstrate weaker repayment consistency.

🔍 Summary Table
| Key Insight                                              | Customer Segment                                       | Influencing Variables                                          | Potential Impact                                                    |
| -------------------------------------------------------- | ------------------------------------------------------ | -------------------------------------------------------------- | ------------------------------------------------------------------- |
| High-risk customers have elevated delinquency likelihood | Age < 30, 2+ missed payments, credit utilization > 50% | Missed Payments, Credit Utilization, Age, Debt-to-Income Ratio | Targeted outreach could reduce 30-day delinquency rates by over 10% |

💡 Recommendation Framework
🎯 Restated Insight:

Customers under 30 years old with 2+ missed payments and credit utilization above 50% face a significantly higher delinquency risk.

✅ Proposed Action:

Implement a 6-week SMS outreach campaign to engage this high-risk segment and encourage timely repayment.
| SMART Criteria | Description                                                                            |
| -------------- | -------------------------------------------------------------------------------------- |
| **Specific**   | Target customers under 30 with 2+ missed payments and high credit utilization          |
| **Measurable** | Aim to reduce 30-day delinquency rate by **10%**                                       |
| **Actionable** | Utilize existing SMS communication channels                                            |
| **Relevant**   | Aligns with Geldium’s business goal to reduce delinquency and improve repayment health |
| **Time-Bound** | Complete campaign execution within **6 weeks**                                         |

💼 Business Justification:

This data-backed intervention is cost-effective, scalable, and customer-centric. It focuses on proactive engagement rather than punitive measures, strengthening customer trust while improving loan recovery rates.

🤖 Ethical & Responsible AI Considerations
| Concern                   | Description                                                             | Mitigation                                   |
| ------------------------- | ----------------------------------------------------------------------- | -------------------------------------------- |
| **Bias**                  | Risk of underrepresentation or misclassification due to historical bias | Conduct fairness audits and bias testing     |
| **Explainability**        | Stakeholders need to understand model outputs                           | Use Logistic Regression for transparency     |
| **Responsible Action**    | Avoid punitive actions based solely on AI outputs                       | Human review before final decisions          |
| **Data Privacy**          | Sensitive financial data must be protected                              | Anonymize customer data and comply with GDPR |
| **Continuous Monitoring** | Model may degrade over time                                             | Regular retraining and drift detection       |

📄 Deliverables

Report: Task3_Business_Summary_Report_Formatted.docx

Dataset Used: Delinquency_prediction_dataset.xlsx

Previous Tasks:

Task 1 – EDA and Data Quality Review

Task 2 – Predictive Model Plan

🏁 Outcome

This task demonstrates how data insights can directly drive strategic business actions, enabling Geldium to make fair, efficient, and explainable credit risk management decisions.
