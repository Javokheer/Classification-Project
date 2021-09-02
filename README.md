# Classification project
**Bank Marketing Prediction**

Term deposits are a major source of income for a bank. 
A term deposit is a cash investment held at a financial institution. 
Your money is invested for an agreed rate of interest over a 
fixed amount of time, or term. The bank has various outreach 
plans to sell term deposits to their customers such as email 
marketing, advertisements, telephonic marketing, and digital 
marketing.

Telephonic marketing campaigns still remain one of the most 
effective way to reach out to people. However, they require 
huge investment as large call centers are hired to actually 
execute these campaigns. Hence, it is crucial to identify the 
customers most likely to convert beforehand so that they can be 
specifically targeted via call.



# Task
The data is related to direct marketing campaigns (phone calls) 
of a Portuguese banking institution. The classification goal is 
to predict if the client will subscribe to a term deposit 
(variable y).

# Dataset


The data is related to the direct marketing campaigns of a 
Portuguese banking institution. The marketing campaigns were 
based on phone calls. Often, more than one contact to the same 
client was required, in order to access if the product 
(bank term deposit) would be ('yes') or not ('no') subscribed by
 the customer or not. The data folder contains two datasets:-

train.csv: 45,211 rows and 18 columns ordered by date (from May 2008 to November 2010)
test.csv: 4521 rows and 18 columns with 10% of the examples (4521), randomly selected from train.csv

# Detailed Column Descriptions

This [dataset](https://www.kaggle.com/prakharrathi25/banking-dataset-marketing-targets?select=train.csv) 
is publicly available for research. 

bank client data:

- **age:** (numeric)
- **job:** type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur",...,"student")
- **marital:** marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
- **education:** (categorical: "unknown","secondary","primary","tertiary")
- **default:** has credit in default? (binary: "yes","no")
- **balance:** average yearly balance, in euros (numeric)
- **housing:** has housing loan? (binary: "yes","no")
- **loan:** has personal loan? (binary: "yes","no")
**Related with the last contact of the current campaign:**
- **contact:** contact communication type (categorical: "unknown","telephone","cellular")
- **day:** last contact day of the month (numeric)
- **month:** last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec")
**Other attributes:**
- **campaign:** number of contacts performed during this campaign and for this client (numeric, includes last contact)
- **pdays:** number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
- **previous:** number of contacts performed before this campaign and for this client (numeric)
- **poutcome:** outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

Output variable (desired target):
- **y** - has the client subscribed a term deposit? (binary: "yes","no")

Missing Attribute Values: None

# Table of Content

 `Importing Libraries`

 `EDA`

`Data Wranging` 
 
 `Modelling` 
 
 `Model Evaluation`
## Tech Stack

 - [Python 3.9.5](https://www.python.org/)
 - [Numpy 1.19.5.](https://numpy.org/)
 - [Pandas 1.2.4.](https://pandas.pydata.org/)
 - [Seaborn 1.7.0.](https://seaborn.pydata.org/)
 - [Matplotlib 3.4.2.](https://matplotlib.org/)


  
## Authors

- [@javokheer](https://www.github.com/Javokheer)

  
