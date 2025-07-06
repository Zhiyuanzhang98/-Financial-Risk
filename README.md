Overview:

This report is based on the "Exploratory Analytical Research Report on Predicting User Loan Defaults by Internet Financial Risk Control Based on Big Data Technology", which aims to explore how to predict the risk of loan defaults in Internet finance using big data technology.The report analyses in detail the key aspects of the research background, technologies used, data sources, data processing, feature engineering, machine learning model building, prediction and model evaluation.By comparing the differences between traditional financial risk control and big data risk control, it describes the application of big data risk control in Internet finance, and shows how to predict loan defaults more effectively through specific data analysis, feature engineering and machine learning model building, with a view to providing lending companies with a more accurate means of risk control.

Main content:

1. Research background and overview

- Research background: the rapid development of Internet finance has brought new challenges in risk control, and big data risk control models have become the focus of the industry.While traditional risk control relies on financial data with strong credit attributes, big data risk control identifies borrower risk through multi-dimensional data and reveals the relationship between behavioural characteristics and credit risk.
- Research Summary: To cope with the default risk in the loan business, lending companies need to establish an effective vetting system.Automatic auditing of lender information through machine learning models can be more effective in risk assessment and reduce manpower costs.

2. Key technologies and data sources

- Technology used: the study is based on Python language, using Jupyter Notebook for data analysis, involving numpy, pandas, matplotlib, seaborn, sklearn and other libraries.
- Data source: the data comes from the loan records of a credit platform, containing more than 1.2 million data records and 47 variables, 15 of which are anonymous.

3. Data Analysis and Cleaning

- Data volume and features: the training set contains 800,000 data records and the test set contains 400,000 data records.The data features include integer, floating point and text type.
- Missing value processing: the missing values are analysed and cleaned by filling the mean value or deleting useless columns.
- Text-type data processing: Numerical processing of text-type data using label encoder and one-hot encoding.
- Feature correlation analysis: correlation analysis is used to filter out the features with higher correlation with default, such as subGrade, interestRate and term.

4. Feature engineering

- Feature Dimensionless: Normalise features to balance the contribution of each feature and avoid numerical problems.
- Feature Selection: select features with higher correlation with loan defaults, such as dti, interestRate, etc. through feature importance assessment.

5. Establish machine learning model

- Model selection: random forest, logistic regression and gradient boosting tree classifiers are selected as preliminary models.
- Model tuning: model tuning through cross-validation to optimise model performance.
- Model Effect Comparison: The model after data cleaning, feature engineering and outlier processing is the most effective.

6. Model Prediction and Evaluation

- Prediction method: Use predict_proba method to return the predicted probability and distinguish between non-default and default.
- Model evaluation: the AUC evaluation model is used to evaluate the performance of the model in the case of imbalance between positive and negative sample ratios.
Conclusion:

This study has successfully explored an effective method for predicting user loan defaults based on big data technology for Internet financial risk control through detailed data analysis, feature engineering and machine learning model building.The results show that the accuracy of loan default prediction can be significantly improved through the comprehensive analysis of multi-dimensional data and the optimisation of the machine learning model, providing a more scientific risk control strategy for lending companies.
