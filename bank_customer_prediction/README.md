## 📁 About The Data Folder

This project is actually divided into three parts:

  1.built the machine learning model to predict the type of card the customer may issue.

  2.built a Web application on the Django to mount the prediction model.

  3.Deployed the Diango project on Heroku through github.
	
## Dataset 
Data Dictionary:

* CLIENTNUM: Client number. Unique identifier for the customer holding the account

* Attrition_Flag: Internal event (customer activity) variable - if the account is closed then 1 else 0

* Customer_Age: Age in Years

* Gender: Gender of the account holder

* Dependent_count: Number of dependents

* Education_Level: Educational Qualification of the account holder

* Marital_Status: Marital Status of the account holder

* Income_Category: Annual Income Category of the account holder

* Card_Category: Type of Card

* Months_on_book: Period of relationship with the bank

* Total_Relationship_Count: Total no. of products held by the customer

* Months_Inactive_12_mon: No. of months inactive in the last 12 months

* Contacts_Count_12_mon: No. of Contacts in the last 12 months

* Credit_Limit: Credit Limit on the Credit Card

* Total_Revolving_Bal: Total Revolving Balance on the Credit Card

* Avg_Open_To_Buy: Open to Buy Credit Line (Average of last 12 months)

* Total_Amt_Chng_Q4_Q1: Change in Transaction Amount (Q4 over Q1)

* Total_Trans_Amt: Total Transaction Amount (Last 12 months)

* Total_Trans_Ct: Total Transaction Count (Last 12 months)

* Total_Ct_Chng_Q4_Q1: Change in Transaction Count (Q4 over Q1)

* Avg_Utilization_Ratio: Average Card Utilization Ratio

The data set in particular has a lot of columns, it contains how much the card is being

used, on what basis the card is being used, how much the customer is paying for that and if customer wants to renew the card or maybe upgrade.

All of that type of information is present.	
	
## Machine learning model : RandomForest Classification

