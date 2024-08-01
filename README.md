# deep-learning-challenge

Module 21: Neural Networks and Deep Learning



### **Overview:**

_AlphabetSoupCharity_Optimization.ipynb_ takes the historical data from a nonprofit foundation Alphabet Soup and creates a binary classifier to help predict whether an applicant will be successful if funded.  The historical data is found in _charity_data.csv_ and has the following metadata:

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special considerations for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively




### **Results:** 

Data Preprocessing


* The target variable in the model is IS_SUCCESSFUL since it indicates if applicant was successful.

* The feature variables in the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE,
       ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS.
       
* The variable that were dropped from the model are EIN and NAME because they were not utilized.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
