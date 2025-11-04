# Background and Context

Businesses like banks that provide service have to worry about the problem of 'Churn' i.e. customers leaving and joining another service provider. It is important to understand which aspects of the service influence a customer's decision in this regard. Management can concentrate efforts on the improvement of service, keeping in mind these priorities.

# Objective

Given a Bank customer, build a neural network-based classifier that can determine whether they will leave or not in the next 6 months.

# Data Description

The case study is from an open-source dataset from Kaggle. The dataset contains 10,000 sample points with 14 distinct features such as CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance, etc.
* __CustomerId__ : Unique ID which is assigned to each customer
* __Surname__ : Last name of the customer 
* __CreditScore__ : It defines the credit history of the customer.  
* __Geography__ : A customer’s location    
* __Gender__ : It defines the Gender of the customer   
* __Age__ : Age of the customer     
* __Tenure__ : Number of years for which the customer has been with the bank
* __NumOfProducts__ : It refers to the number of products that a customer has purchased through the bank.
* __Balance__ : Account balance
* __HasCrCard__ : It is a categorical variable that decides whether the customer has a credit card or not.
* __EstimatedSalary__ : Estimated salary 
* __isActiveMember__ : It is a categorical variable that decides whether the customer is an active member of the bank or not ( Active member in the sense, using bank products regularly, making transactions, etc )
* __Exited__ : It is a categorical variable that decides whether the customer left the bank within six months or not. It can take two values 
    0=No ( Customer did not leave the bank )
    1=Yes ( Customer left the bank )
