# ML-for-SS
Performing Exploratory Data Analysis and developing basic ML models on sample dataset provided by IBM

# Introduction
## Importance

Churn prediction is crucial for businesses as it helps minimize customer loss and maintain revenue. When customers leave, a business loses both ongoing revenue and incurs costs in acquiring new customers. By accurately identifying potential churners, businesses can take proactive steps like personalized incentives or improved customer support to reduce customer loss and its impact on revenue.

Acquiring new customers is harder and costlier than retaining existing ones. Churn prediction enables businesses to allocate resources efficiently by focusing on retaining customers. This reduces the need for extensive and expensive marketing campaigns, as efforts can be directed towards satisfying and keeping current customers.

Churn prediction also helps businesses assess customer satisfaction levels and identify factors leading to churn. By analyzing customer behavior, feedback, and preferences, businesses can make targeted improvements to enhance the overall customer experience. Addressing these issues boosts customer satisfaction, loyalty, and ultimately improves retention rates.

## Literature Review

Customer churn prediction in the telecom industry has been extensively explored using various machine learning techniques. In the study titled "Customer churn prediction in telecom using machine learning in big data," the authors employed Random Forest and Naïve Bayes algorithms on big data, achieving promising results with high accuracy rates (84% without Social Network Analysis and 93% with it). This demonstrates the effectiveness of these techniques. In another paper titled "Telecom churn prediction and used techniques, datasets, and performance evaluation," a comparison of standalone machine learning techniques, deep learning techniques, and hybrid models with feature extraction tasks was conducted to evaluate their performance. These studies highlight the importance of churn prediction in improving customer retention strategies in the telecom industry.

## Objective

Develop a churn prediction machine learning model using customer data to identify at-risk customers, enabling organizations to take preventive measures and improve customer retention for sustainable revenue growth.

## Data Source

The data used in this project is one of IBMs Sample Dataset and is publicly available on Kaggle at the following link:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Content:

Each row represents a client, and each column provides the attributes of that customer as defined in the column Metadata.

The data set contains information on:

1. Customers who left during the last month - the Churn Services column - phone, multiple lines, internet, online security, online backup, device protection, tech support and streaming TV and films
2. Customer account information, including length of service, contract, payment method, paperless billing, monthly charges, and total charges.
3. Customers' demographic information - gender, age range, and whether or not they have partners or dependents

There are 18 Categorical features and 3 numerical features (SeniorCitizen, tenure, MonthlyCharges)
