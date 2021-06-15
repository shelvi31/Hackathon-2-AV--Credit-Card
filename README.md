# Hackathon-2-AV--Credit-Card


**Credit Card Lead Prediction
**
Credit Card Lead Prediction Happy Customer Bank is a mid-sized private bank that deals in all kinds of banking products, like Savings accounts, Current accounts, investment products, credit products, among other offerings.

The bank also cross-sells products to its existing customers and to do so they use different kinds of communication like tele-calling, e-mails, recommendations on net banking, mobile banking, etc.

In this case, the Happy Customer Bank wants to cross-sell its credit cards to its existing customers. The bank has identified a set of customers that are eligible for taking these credit cards.

Now, the bank is looking for your help in identifying customers that could show higher intent towards a recommended credit card, given:

Customer details (gender, age, region etc.) Details of his/her relationship with the bank (Channel_Code,Vintage, 'Avg_Asset_Value etc.)

Dataset Dictionary:
ID: Unique Identifier for a row

Gender: Gender of the Customer

Age: Age of the Customer (in Years)

Region_Code: Code of the Region for the customers

Occupation: Occupation Type for the customer

Channel_Code: Acquisition Channel Code for the Customer (Encoded)

Vintage: Vintage for the Customer (In Months), How old is customer registered with bank

Credit_Product: If the Customer has any active credit product (Home loan,Personal loan, Credit Card etc.)

Avg_Account_Balance: Average Account Balance for the Customer in last 12 Months

Is_Active: If the Customer is Active in last 3 Months

Is_Lead(Target): If the Customer is interested for the Credit Card

 - 0 : Customer is not interested
 - 1 : Customer is interested
My Inferences from Data Dictionary:
Seeing the Data Dictionary, I can very well Conclude the following variables to be of great importance in prediction whether a customer avails for a credit card or not as per the priority:

Credit_Product
Is_Active
Avg_Account_Balance
Occupation
Though other data points can also contribute in prediction, but as far my inference these should be the most important ones.

Let's get the wheels rolling now...........

![image](https://user-images.githubusercontent.com/66025137/122057697-887ebe80-ce08-11eb-8c1d-1d5f9cff1ac7.png)

