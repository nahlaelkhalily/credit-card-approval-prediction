# credit-card-approval-prediction
# Abstract:
In response to the limitations of traditional credit scoring systems, a modern approach utilizing 
machine learning techniques has been employed to revolutionize credit evaluation procedures. By 
analyzing historical customer data with algorithms such as XGBoost, Light Gradient Boosting 
Machine (LGBM), Decision Trees (DT), Random Forests (RF), Support Vector Machines (SVM), 
and Logistic Regression (LR), significant patterns influencing credit card approval decisions have 
been identified. Advanced techniques including the Synthetic Minority Over-sampling Technique 
(SMOTE) for data imbalances, Weight of Evidence (WoE) for strategic feature selection, and 
vintage analysis for long-term credit performance assessment were utilized. Following extensive 
testing, XGBoost emerged as the most efficient algorithm, achieving an impressive accuracy score 
of 92.8% and an F1 score of 92.9%. This research breakthrough equips financial institutions with 
a powerful tool to minimize risks and enhance customer satisfaction in credit evaluations, aligning 
with the broader trend of leveraging machine learning to address credit risk assessment challenges

# Methodology
![Flow chart](https://github.com/nahlaelkhalily/credit-card-approval-prediction/assets/148993961/0cc7c3a1-e1d1-43ac-9256-d8d6585024fc)

The process of customer credit card approval begins with data collection, followed by crucial preprocessing steps such as handling missing values and outliers. The data is then split into training and testing datasets, and multiple machine learning algorithms, including support vector machines, logistic regression, extreme gradient boosting, random forests, and decision trees, are trained. The best-performing algorithm is chosen as the champion model, and a dashboard is built to visualize the model's results, allowing for informed decision-making based on the model's predictions and performance

# vintage analysis
![vintage analysis](https://github.com/nahlaelkhalily/credit-card-approval-prediction/assets/148993961/9efd3333-a02b-4cfd-b724-0402e9488a77)

The provided vintage analysis graph illustrates the cumulative percentage of bad customers, defined as those more than 60 days past due, over time. The graph indicates a steady increase in the percentage of bad customers over the past few months. This rise could be attributed to various factors, such as changes in the economy, alterations in the company's credit policies, or shifts in the quality of its customer base. Understanding and addressing the underlying reasons for this trend is crucial for effective risk management and decision-making.

# Dashboard
![Credit Card Dahboard](https://github.com/nahlaelkhalily/credit-card-approval-prediction/assets/148993961/7732954f-2114-476f-bd18-36d978d22d0e)

Utilizing data analytics, a comprehensive dashboard identifies six key factors influencing credit card approval: age, income, gender, reality, marital status, and work experience. The dashboard discerns that approval probability rises with age until reaching a plateau, and individuals with a sense of financial responsibility are more inclined to apply. Gender disparity in applications is evident, with males exhibiting a higher average income. Furthermore, work experience and income level play significant roles, as applicants with 5-10 years of experience and an income exceeding 5 million are more likely to secure approval. This dashboard is poised to enhance the efficacy and precision of the credit card approval process, enabling informed decision-making based on the analyzed factors.
