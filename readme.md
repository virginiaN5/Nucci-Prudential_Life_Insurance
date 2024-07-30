The Kaggle competition chosen is hosted by Prudential, one of the largest issuers of life insurance in the USA. The project aims to develop a predictive model that can be used to identify risk and eligibility of a customer in a faster way to speed up the insurance application process, that otherwise can be discouraging for customers. 
Given over a hundred variables describing attributes of life insurance applicants, the task is to predict the "Response" variable for each Id in the test set, where "Response" is an ordinal measure of risk that has 8 levels (from the kaggle competition website, https://www.kaggle.com/competitions/prudential-life-insurance-assessment/overview).
The project is therefore structured following the stages of the analytic pipeline, such as:
- Data Acquisition
- Data Visualization
- Data Preprocessing
- Data Modeling
- Performance Evaluation

The evaluation is done is terms of the quadratic weighted kappa, a score that expresses the level of agreement between two annotators on a classification problem, and that ranges from 0 to 1, where 0 and 1 represent respectively random and complete agreement. The two annotators are the actual and predicted risk.

For this project, the best modeling tecnique implemented is XGBoost, that leads to a quadratic weighted kappa score of 0.573 .  
