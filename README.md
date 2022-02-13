# TEAM_C_data606
### This project is part of DATA-606 Capstone project -TEAM-C


__Title__: **End to End data science application which can be leveraged by banks to assess creditworthiness, lower bad debt burden, and increase the trust in the existing data rather than document-based assessment**. 
 

 ![1_ZQ25X7Qnq6ui83yc8RB5pQ](https://user-images.githubusercontent.com/91147579/153736327-3ce3b9dd-2e12-4430-83a6-c9e17aa30c36.png)

__Background Information__: Money lending has been a prominent activity to make money out of money.  Institutional banking agencies & many individuals are pursuing this activity to make themselves profitable. Though, this activity has many upsides in terms of investing money that beats the interest rates in the market. But, there are also customers or borrowing agencies who default the loans either intentionally or eventually depending upon the circumstances thus making loans defaulting rate to 6%.  Thus, it became imperative to validate the borrowing credentials before issuing the loans or lending money directly. 

__Severity of the issue__: If loan default occurs continuously it becomes a red flag for lenders and they cannot issue new or more loans to new customers and as well as the capital capacity of their company will fall eventually as investors will back out investing money in the company with an increasing amount of loan defaults. And finally, it leads to more debt on the company intern which leads to losses to the company. To overcome all of these issues we need to have a proper mechanism to implement certain latest methods in the technology to predict the chances of defaulting particular loan so that we can avoid sanctioning that particular loan to be better in the market as well investors perspective for future investments for that particular bank.

__Goals of the Project__: We want to help the lenders or banking institutions to evaluate their customers by predicting whether they default on the loan or not. This in turn increases the credibility of the banks in the public if they lower their loan defaulters.

![determining-customer-creditworthiness thumb 1280 1280](https://user-images.githubusercontent.com/91147579/153737030-54ff439d-1c8d-4f8c-aa0e-e9209b11c5c5.png)


__Dataset Description__: 

ID: Customer ID of Applicant

year: Year of Application

loan_limit: Cash Flow or Net Cash Flow type

gender: Applicant's gender

approv_in_adv: Is loan pre-approved or not

loan_type: Type of loan

loan_purpose: Purpose of loan

Credit_Worthiness: Credit worthiness of the applicant

open_credit: Type of Credit (Open credit or Non open credit)

business_or_commercial: Usage type of the loan amount

loan_amount: The exact loan amount

rate_of_interest: Rate of interest of the loan 

Interest_rate_spread: Spread of interest rate by banks

Upfront_charges: Up front loan sanctioning charges

lump_sum_payment: Down payment for the loan 

property_value: Collateral value

construction_type: Collateral construction type

age: Age of applicant

Security_Type: Type of Collatoral

status: Loan status (Approved/Declined)


__Data source__- https://www.kaggle.com/yasserh/loan-default-dataset

__Unit of Analysis__: Loan record of applicant.

__Number of observations to be analysed__: 148671

__Output Variable__: Loan status

__Models to be used__: 

1. Random Forest with Grid search CV

2. Logistic Regression with Grid search CV

3. Support Vector Machine with Grid search CV

4. K Nearest Neighbors with Grid search CV

5. Bagging with Base estimator as Random Forest

6. Bagging with Base estimator as Logistic Regression

7. AdaBoost Classifier

8. Multilayer Perceptron Classifier

9. Neural Networks

10. Tensor Flow.

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

12) Building a dashboard which helps banking stakeholders to access the status of creditworthiness.
