# Bank Customer Attrition Analysis  
Exploratory Data Analysis (EDA) Project by Moyin Odumewu  
Feb 2024

---

## Project Summary  
This project analyzes a banking customer dataset (~10,000 records, 18 features) to identify behavioral and financial patterns associated with customer attrition (churn). The aim is to surface actionable insights that support retention strategies, improved product engagement and risk management.

---

## Objectives  
- Understand customer demographics, financial behavior and product usage.  
- Explore how factors like age, credit score, account balance and product count relate to churn.  
- Provide data-driven recommendations to reduce attrition, increase product penetration and boost customer loyalty.

---

## Tools & Technologies  
- Python (Pandas, NumPy)  
- Matplotlib, Seaborn  
- Google Colab for development and notebook sharing  

---

## Dataset Details  
- 10,000 customer records, each with 18 variables including:  
  - CustomerId, Geography, Age, CreditScore, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, Exited (Churn), etc.  
- No missing values; duplicates were checked and cleaned.  
- Binary variables encoded as “Yes”/“No” for clarity.

---

## Methodology  
1. **Data Cleaning & Preparation**  
   - Validated data types, renamed columns for clarity.  
   - Converted binary numeric indicators to categorical labels (“Yes”/“No”).  
   - Verified and dropped duplicates; dataset ready for analysis.  
2. **Exploratory Data Analysis (EDA)**  
   - Univariate analysis: distributions of Age, CreditScore, Balance, NumOfProducts, PointsEarned.  
   - Categorical analysis: Geography, Gender, HasCrCard, IsActiveMember, CardType, Churn status.  
   - Bivariate/Multivariate analysis: boxplots comparing churn vs Age, CreditScore, Balance; correlation matrix heatmap.  
   - Insight generation: identifying higher risk segments for churn.  

---

## Key Findings  
- Customers with **zero account balance** showed a markedly higher rate of churn than those with positive balances.  
- **Lower credit scores** are associated with increased churn — riskier credit profiles tended to exit more frequently.  
- Older customers (50+ years) churned at higher rates relative to younger cohorts.  
- Majority of customers hold **only 1–2 products**, indicating low product diversification — these lower-engagement customers are more prone to attrition.  
- Overall correlation across features is weak; the dataset suggests that many variables individually have limited predictive power, and deeper modeling or feature engineering may be needed.

---


### Churn Distribution  

## Visualizations  
![Age vs Churn](https://github.com/M0Data/Bank-customers-Attrition--EDA/blob/main/Agevschurn.png)

![Balance vs Churn](https://github.com/M0Data/Bank-customers-Attrition--EDA/blob/main/BalancevsChurn.png)

![EDA](https://github.com/M0Data/Bank-customers-Attrition--EDA/blob/main/eda.png)

![Correlation Heatmap](https://github.com/M0Data/Bank-customers-Attrition--EDA/blob/main/corrolation.png)

---

## Recommendations  
Based on the insights derived from the EDA:

- Focus retention efforts on **zero-balance customers** and create financial engagement incentives.  
- Strengthen credit advisory or credit-improvement strategies for customers with **low credit scores**, reducing churn in this segment.  
- Improve product engagement by **cross-selling or bundling services** for customers with only 1–2 products.  
- Implement personalized outreach or loyalty programs targeting **older customers** who exhibit higher churn probability.  
- Use insights as a foundation for building a **predictive churn model** to support targeted marketing and proactive retention.

---

## Project Notebook  
Full notebook is available here:  
[Exploring Bank Customer Attrition — EDA Project](https://github.com/M0Data/Bank-customers-Attrition--EDA/blob/main/Exploring_Bank_Customer_Attrition_EDA_project.ipynb)

---

## How I Can Help Organizations  
With strong analytical and problem-solving skills, I help organizations:

- Turn raw data into actionable business insights.  
- Identify customer behavior patterns that inform product, marketing, and retention decisions.  
- Build automated reports and dashboards that support data-driven strategy.  
- Support decision-makers with clear storytelling, risk identification, and improvement recommendations.

---

## About Me  
**Moyin Odumewu**  
Data Analyst — Python | SQL | Power BI | EDA & Reporting  
GitHub: https://github.com/M0Data  
Email: odumewumoyin@gmail.com

---

Thank you for reviewing this project. Contributions, feedback, and collaboration are welcome.

