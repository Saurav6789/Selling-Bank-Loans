# Selling-Bank-Loans

Data Description:
The file Bank.xls contains data on 5000 customers. The data include customer
demographic information (age, income, etc.), the customer's relationship with the bank
(mortgage, securities account, etc.), and the customer response to the last personal loan
campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted
the personal loan that was offered to them in the earlier campaign.
Domain:
Banking
Context:
This case is about a bank (Thera Bank) whose management wants to explore ways of
converting its liability customers to personal loan customers (while retaining them as
depositors). A campaign that the bank ran last year for liability customers showed a
healthy conversion rate of over 9% success. This has encouraged the retail marketing
department to devise campaigns with better target marketing to increase the success
ratio with minimal budget.
Attribute Information:
 ID : Customer ID
 Age : Customer's age in completed years
 Experience : #years of professional experience
 Income : Annual income of the customer ($000)
 ZIP Code : Home Address ZIP code.
 Family : Family size of the customer
 CCAvg : Avg. spending on credit cards per month ($000)
 Education : Education Level. 1: Undergrad; 2: Graduate;
 3: Advanced/Professional
 Mortgage : Value of house mortgage if any. ($000)
 Personal Loan : Did this customer accept the personal loan offered in the
 last campaign?
 Securities Account : Does the customer have a securities account with the bank?
 CD Account : Does the customer have a certificate of deposit (CD)
 account with the bank?
 Online : Does the customer use internet banking facilities?
 Credit card : Does the customer use a credit card issued by 
 UniversalBank?
Learning Outcomes:
 Exploratory Data Analysis
 Preparing the data to train a model
 Training and making predictions using a classification model
 Model evaluation
Objective:
The classification goal is to predict the likelihood of a liability customer buying personal
loans.
Steps and tasks:
1. Read the column description and ensure you understand each attribute well
2. Study the data distribution in each attribute, share your findings
3. Get the target column distribution. Your comments
4. Split the data into training and test set in the ratio of 70:30 respectively
5. Use different classification models (Logistic, K-NN and Naïve Bayes) to predict
the likelihood of a liability customer buying personal loans
6. Print the confusion matrix for all the above models
7. Give your reasoning on which is the best model in this case and why it performs
better?
