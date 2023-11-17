## Databel Customer Churn Analysis using Tableau

[fullfilechurn1]: https://drive.google.com/file/d/1Y-xXLQHMWtyvg70N0qdVavD56_0l834N/view?usp=sharing

>[!NOTE]
**For a comprehensive analysis, please refer to this [Full Report][fullfilechurn1] document.**

[churntableau]: https://public.tableau.com/views/DatabelCustomerChurnAnalysis_16972128466670/CustomerChurn?:language=en-GB&:display_count=n&:origin=viz_share_link

**Tableau URL: [Databel Customer Churn Analysis Dashboard][churntableau]**

### 1. Introduction

Undertaken with a fictional churn dataset from a Telecom provider named Databel to analyze, this project delves deep into the phenomenon of customer churn. The dataset consists of 29 different columns with one row per customer, which provides a comprehensive view of each customer through individual rows to retain valuable customers and maintain a strong relationship with their customer base.

### 2. Definition of "Churn"

According to Investopedia, the Churn Rate, also known as the rate of attrition or customer churn, is the rate at which customer stop doing business with an entity. It is commonly expressed as the percentage of service subscribers who discontinue their subscriptions within a given period.

The churn rate formula is the number of customers lost during the period divided by total number of customers. Churn rate is commonly expressed as a percentage used to evaluate the retention success and potential growth or decline of a business’s customer base. A high churn rate may indicate customer dissatisfaction, while a low rate suggests customers are satisfied and remain loyal to the product or service. Minimizing the churn rate is crucial for sustained growth and profitability.

Churn Analysis is the process of evaluating and understanding the reasons and patterns behind customer choosing to end their relationship with a company or service over a specific period. Churn analysis is including:

  - Descriptive analytics: It is used to understand the current churn rate and profile of churned customers.
  - Predictive analytics: It is used to apply machine learning models to predict potential churn based on customer behavior and characteristics.
  - Prescriptive analytics: It is used to recommend specific actions to prevent or reduce churn.

### 3. Objective

The primary objective of the customer churn analysis dashboards is to gain a comprehensive understanding of the factors and patterns leading to customer attrition. By segmenting and analyzing data across various dimensions such as age, contract type, data consumption, payment method, and customer service interactions, to pinpoint high-risk groups and the predominant reasons for churn.

### 4. Data Source

The dataset used in this project is a fictional churn dataset from a Telecom provider named Databel, the dataset consists of 29 columns or variables and 6687 rows of customer records with no time dimension. 

### 5. Data Preparation

- Data check: to double check the duplicate rows in dataset by reviewing the number of Customer ID, which is equal to the count of unique customer ID.
- Churn label column indicates “Yes” or “No”, so it was converted into binomial column 0 for not churned or 1 for churned.
- Create a measure for the number of churn customers.
- Calculating Churn rate by dividing the total number of churned customers with the total number of customers.

### 6. Dashboard Exploration and Recommendation

- The overview dashboard reveals a 29% customer churn rate, is primarily driven by competition, service quality, and unclarified customer concerns. With month-to-month contracts yielding the highest churn and California showing a concerning about 63% churn rate. It is suggested to improve the offerings, promote longer-term contracts, and streamline feedback processes.
  
- The age and group dashboard, the customer base is particularly in middle-aged customers, specifically those in their late forties. The churn rates are relatively consistent among younger to middle-aged groups. There is a considerable increase in churn rate among customers aged 70 and older. Furthermore, customers not associated with any group have remarkable high churn rate about 32%, whereas those in specific groups shows much lower churn rates. Based on the information, it is recommended to include support for elderly, targeted retention strategies for forties age group, and further investigate on Group 5.
  
- The payment methods, contract types, and data plan dashboard highlights that customer churn rates are closely linked to payment methods, international activity, and data plan alignment. The long-term contracts and credit card payments reduce churn, mismatches in international service increase churn, and data consumption habits influence customer loyalty. To boost retention, should focus on personalized service offerings and align services with customers’ actual needs.
  
- The customer service calls across states dashboard brings that a higher frequency of customer service interactions correlates with an increased of churn. Customers who eventually churn make more customer service call, with an average ranging from 0.8 to 3 calls, whereas those who remain engaged fewer calls below 1. California (CA) presents an anomaly, despite having a low average of service calls, it records a high churn rate of 63%. This suggests that other factors, unrelated to customer services might be influencing churn in this state. It is recommended that proactive engagement with frequent callers to prevent churn and investing in better customer service. Additionally, CA needs a further detailed analysis and a potential need for more customer outreach efforts.
