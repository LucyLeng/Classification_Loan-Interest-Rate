# Classification_Loan-Interest-Rate
Using machine learning models and feature engineering to find pattern and  predict loan interest rate. Compare models and present the results 

This project analyzes a publicly available dataset consisting of 9578 records of data and 14 columns of variables provided by **LendingClub.com** from 2007 to 2012. This project will provide a detailed analysis investigating the relative variables’ influence on the interest rate to help the business determine which areas to focus on when deciding the interest rate of loans being borrowed to clients.

**Project Summary:**<br>
Project Name: Loan Interest Rate Risk Analysis<br>
Data Source: Kaggle dataset from LendingClub.com<br>
Business Objectives: Identify key variables influencing loan interest rates.<br>

**Key Achievements:**<br>
Conducted Exploratory Data Analysis (EDA) using Python.<br>
Employed Synthetic Minority Over-sampling Technique (SMOTE) to address imbalanced data.<br>
Implemented various classification models for risk analysis.<br>

**Modeling Insights:**<br>
Logistic Regression Model: Identified "purpose_small_business," "purpose_all_others," and "purpose_major_purchase" as high-interest loan categories.<br>
Decision Tree Model: Emphasized the significance of FICO scores and excluded small business loans as favorable.<br>
Random Forest Model: Highlighted the importance of FICO score, credit policy, and installment payments.<br>
Gradient Boosting Model: Stressed the impact of FICO scores and installment payments on interest rates.<br>
Achieved an impressive accuracy rate of 90.08% with the Gradient Boosting Model.<br>

**Recommendations:**<br>
Loan Approval Criteria: Suggested continuing the use of FICO scores and considering loan purpose as crucial factors in loan approval decisions.<br>
Enhanced Analysis: Advised incorporating additional factors such as geographic location, interest rate type, and loan term for a more comprehensive risk assessment.<br>

