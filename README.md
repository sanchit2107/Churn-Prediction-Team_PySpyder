# Hackathon19-Churn-Prediction 
:rocket:
***Machine Learning model that can predict the customers with high probability of churn.***

## Business Scenario
Our client, ElectricCo, is a major utility company providing gas and electricity to corporate, SME and residential customers. In recent years, post-liberalization of the energy market in Europe, ElectricCo has had a growing problem with increasing customer defections above industry average. They would like to identify the drivers of this problem and to devise and implement a strategy to counter it. The churn issue is most acute in the SME division and thus they want it to be the first priority. The head of the SME division has asked whether it is possible to predict the customers which are most likely to churn so that they can trial a range of pre-emptive actions.

### Our task  :wave:
The client also would like to answer the following questions:
1. What are the most explicative variables indicating churn?
2. Is there a correlation between subscribed power and consumption?
3. Is there a link between sales channel and churn?
4. Build a machine learning model that can predict the customers with high probability of churn.

> The first stage is to establish the viability of such a model. For training your model you are provided with a dataset which includes features of SME customers in January 2016 as well as the information about whether or not they have churned by March 2016. In addition to that you have received the prices from 2015 for these customers. While it is not mandatory, but you are encouraged to test multiple algorithms to build predictive model.

> __Using the trained model you shall “score” customers in the verification data set (provided in the eponymous file) and put them in descending order of the propensity to churn. You should also classify these customers into two classes: those which you predict to churn are to be labelled "1" and the remaining customers should be labelled "0" in the result template.__

## Information contained in the data set

The below table describes all the data fields which are found in the data (across three files). You will notice that the contents of some fields are meaningless text strings. This is due to "hashing" of text fields for data privacy. While their commercial interpretation is lost as a result of the hashing, they may still have predictive power.

A whole host of rich investigations are possible. Your ideas on what some next steps could be, armed with such data is also of interest.

## Data fields and their description
There are 16096 SME customers present. 15500 customers considering for Model training, validation and testing and 596 customers considered for predicting going to churn in next 3 months or not (where output is not present for these 596 customers)

#### Table: Hackthon_case_training_data 
*The data provided for all the 16096 customers*

#### Table2: Hackthon_case_training_hist_data
*The data provided for all the 16096 customers 
Every customer have last 12 months data (12 rows of data for each Customer )*

#### Table3: Hackthon_case_training_output
*The output provided for only 15500 customers*


