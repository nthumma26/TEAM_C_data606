# TEAM_C_data606
### This project is part of DATA-606 Capstone project -TEAM-C


__Title__: End to End data science application which can be leveraged by banks to assess creditworthiness, lower bad debt burden, and increase the trust in the existing data rather than document-based. 
 

 ![1_ZQ25X7Qnq6ui83yc8RB5pQ](https://user-images.githubusercontent.com/91147579/153736327-3ce3b9dd-2e12-4430-83a6-c9e17aa30c36.png)

__Background Information__: Money lending has been a prominent activity to make money out of money.  Institutional banking agencies & many individuals are pursuing this activity to make themselves profitable. Though, this activity has many upsides in terms of investing money that beats the interest rates in the market. But, there are also customers or borrowing agencies who default the loans either intentionally or eventually depending upon the circumstances thus making loans defaulting rate to 6%.  Thus, it became imperative to validate the borrowing credentials before issuing the loans or lending money directly. 

__Severity of the issue__: If loan default occurs continuously it becomes a red flag for lenders and they cannot issue new or more loans to new customers and as well as the capital capacity of their company will fall eventually as investors will back out investing money in the company with an increasing amount of loan defaults. And finally, it leads to more debt on the company intern which leads to losses to the company. To overcome all of these issues we need to have a proper mechanism to implement certain latest methods in the technology to predict the chances of defaulting particular loan so that we can avoid sanctioning that particular loan to be better in the market as well investors perspective for future investments for that particular bank.

__Goals of the Project__: We want to help the lenders or banking institutions to evaluate their customers by predicting whether they default on the loan or not. This in turn increases the credibility of the banks in the public if they lower their loan defaulters.

__Dataset Description__: We found the dataset from Kaggle. The size of dataset is 28MB which contains 34 columns namely ID, year, loan_limit, gender, approv_in_adv, loan_type, loan_purpose, Credit_Worthiness, open_credit, business_or_commercial, loan_amount, rate_of_interest, Interest_rate_spread, Upfront_charges, term, Neg_ammortization means Negotiative ammortization, interest_only, lump_sum_payment, property_value, construction_type, occupancy_type, Secured_by, total_units, income, credit_type, credit_score, co-applicant_credit_type, age, submission_of_application, LTV, region, Security_Type, status, dtir_1.

__Data source__- https://www.kaggle.com/yasserh/loan-default-dataset

__Unit of Analysis__: Records of customers data like the data provided during accessing the loan initially.

__Number of observations to be analysed__: 148671

__Output Variable__: Loan status

__Models to be used__: Random Forest with Grid search CV, Logistic Regression with Grid search CV, Support Vector Machine with Grid search CV, K Nearest Neighbors with Grid search CV, Bagging with Base estimator as Random Forest, Bagging with Base estimator as Logistic Regression, AdaBoost Classifier, Multilayer Perceptron Classifier.

__Evaluation metrics to be used__: we are planning to evaluate the metrics such as recall, accuracy, precision, f-1 score, confusion matrix, ROC-AUC scores. After determining the metric to evaluate the model with the help of the business understanding of the domain of the data, we'll figure out the ways to improve the performance of the model.

__Expected Outcomes__: 
1) Importance of business domain understanding in choosing and evaluating the model. 
2) To apply various machine learning models to classify the outcome. 
3) Usage of Various evaluating metrics to determine the performance of the model. 
4) Importance of Various Statistical Analysis Understanding the Dimensionality Reduction. 
5) Understanding the Bias-Variance trade-off. 
6) Application of Principal component analysis. 
7) Usage of Grid search Validations. 
8) Understanding of Various activation functions. 
9) Effectively handling the outliers. 
10) Usage of various hyperparameters. 
11) Analyzing & Visualizing the data.
