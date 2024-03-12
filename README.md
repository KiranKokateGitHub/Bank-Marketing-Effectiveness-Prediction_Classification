# Classification

# Project Name- Bank Marketing Effectiveness Prediction

# Project Type - Classification

# Contribution - Individual

# Team Member 1 - Kiran

# Problem Statement

The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe a term deposit (variable y).

# Project Summary -

This project focused on utilizing machine learning techniques to predict the success of bank marketing campaigns using data from a Portuguese banking institution. The dataset included various input variables such as age, job, marital status, education, balance, and more. The primary objective was to develop a classification model to accurately predict the effectiveness of these campaigns, enabling better targeting of customers.

The dataset consisted of 45,211 observations with 17 columns, including 10 categorical variables (employment, marital status, etc.) and seven numerical variables (age, balance, etc.). Descriptive statistics and visualizations were employed to gain insights and understand potential patterns in the data.

To prepare the data, null values in features like contact, education, and job were replaced with the most frequent values. Features with over 50% null values were removed to avoid impacting model performance. Outliers were handled using the interquartile range method for specific numerical variables.

The analysis revealed that the majority of bank term deposits were made by clients aged 30 to 36. Blue-collar job holders were less likely to subscribe, while those with managerial jobs were more likely. Married clients were the most common and most likely to subscribe, while divorced clients were less likely to do so. Higher education levels increased the likelihood of signing up for a term deposit. Most subscribers had no credit defaults and no housing loans. Having a housing loan reduced the likelihood of subscribing by 51%.

Clients without personal loans were more likely to subscribe, while those with personal loans were less likely. Clients contacted via cellular communication were more likely to subscribe. Subscriptions were higher in May, June, July, August, and April, with May standing out significantly. Subscribers tended to be contacted fewer than three times.

Overall, only 11.7% of clients subscribed, indicating an 88.3% chance of not subscribing. Management-related jobs and tertiary degrees were associated with higher subscription rates. Customers with secondary education were the second most likely to subscribe. Longer phone call durations increased subscription likelihood, with an average of 400 seconds to convey intent.

Customers without any debts were more likely to sign up, while those with both types of loans were less likely to choose a term deposit.

For categorical variables, label encoding was used, and one hot encoding was employed for job and month with many categories. Class imbalance was addressed using SMOTE to balance the target variable.

The data was scaled using MinMaxScaler for uniformity. Various machine learning models i.e Logistic Regression, Random Forest, XGBoost and KNN were trained, and cross-validation improved their performance. XGBoost founds the best model amongst the implmented models, achieving high scores for accuracy, precision, recall, F1 score, and ROC AUC score, all close to 0.93.

In conclusion, the XGBoost classification model successfully predicted the effectiveness of bank marketing campaigns, providing valuable insights for better customer targeting.

