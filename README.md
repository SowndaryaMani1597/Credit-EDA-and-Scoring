# <h1 align='center'> <font size=7> Credit Score EDA Case Study</h1>
<image src="https://edujas.com/en/wp-content/uploads/2022/05/credit_score_illustration_4534754.webp">

## Problem statement</font>

* To conduct a thorough exploratory data analysis (EDA) and deep analysis of a comprehensive dataset containing basic customer details and extensive credit-related information. The aim is to create new, informative features, calculate a hypothetical credit score, and uncover meaningful patterns, anomalies, and insights within the data.

* This case study expects a deep dive into bank details and credit data, creating valuable features, a hypothetical credit score, and uncovering hidden patterns. This involves thorough EDA, strategic feature engineering, model-driven score calculation, and insightful analysis that reveals factors influencing creditworthiness and guides potential risk mitigation strategies.

* Remember, your analysis isn't just about dissecting data but uncovering actionable insights. Create a credit score strategy that you think would be the best and mention your justifications for criteria, weightage for the features
  
### Data Dictionary:


| Column Name               | Description                                                      |
|---------------------------|------------------------------------------------------------------|
| ID                        | Represents a unique identification of an entry                   |
| Customer_ID               | Represents a unique identification of a person                   |
| Month                     | Represents the month of the year                                 |
| Name                      | Represents the name of a person                                  |
| Age                       | Represents the age of the person                                 |
| SSN                       | Represents the social security number of a person                |
| Occupation                | Represents the occupation of the person                          |
| Annual_Income             | Represents the annual income of the person                       |
| Monthly_Inhand_Salary     | Represents the monthly base salary of a person                   |
| Num_Bank_Accounts         | Represents the number of bank accounts a person holds            |
| Num_Credit_Card           | Represents the number of other credit cards held by a person     |
| Interest_Rate             | Represents the interest rate on credit card                      |
| Num_of_Loan               | Represents the number of loans taken from the bank               |
| Type_of_Loan              | Represents the types of loan taken by a person                   |
| Delay_from_due_date       | Represents the average number of days delayed from the payment date |
| Num_of_Delayed_Payment    | Represents the average number of payments delayed by a person    |
| Changed_Credit_Limit      | Represents the percentage change in credit card limit            |
| Num_Credit_Inquiries      | Represents the number of credit card inquiries                   |
| Credit_Mix                | Represents the classification of the mix of credits              |
| Outstanding_Debt          | Represents the remaining debt to be paid (in USD)                |
| Credit_Utilization_Ratio  | Represents the utilization ratio of credit card                  |
| Credit_History_Age        | Represents the age of credit history of the person               |
| Payment_of_Min_Amount     | Represents whether only the minimum amount was paid by the person |
| Total_EMI_per_month       | Represents the monthly EMI payments (in USD)                     |
| Amount_invested_monthly   | Represents the monthly amount invested by the customer (in USD)  |
| Payment_Behaviour         | Represents the payment behavior of the customer (in USD)         |
| Monthly_Balance           | Represents the monthly balance amount of the customer (in USD)   |

### Methodology

**Exploratory Data Analysis (EDA):**

* Performing a comprehensive EDA to understand the data's structure, characteristics, distributions, and relationships.
* Identified and addressed any missing values, mismatch data types, inconsistencies, or outliers.
* Utilized appropriate visualizations (e.g., histograms, scatter plots, box plots, correlation matrices) to uncover patterns and insights.

**Feature Engineering:**

* Created new features that can be leveraged for the calculation of credit scores based on domain knowledge and insights from EDA 
    
**Hypothetical Credit Score Calculation:**

* Developed a methodology to calculate a hypothetical credit score(kinda CIBIL/FICO ranges from 300-850,900) using relevant features (using a minimum of 5 maximum of 10 features) and justified it.

* Explored various weighting schemes to assign scores.
* Provided a score for each individual customer
