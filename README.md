# deep-learning-challenge

Module 21: Neural Networks and Deep Learning



### **Overview:**

_AlphabetSoupCharityCode.ipynb_ takes the historical data from a nonprofit foundation Alphabet Soup and creates a binary classifier to help predict whether an applicant will be successful if funded.  The historical data is found in _charity_data.csv_ and has the following metadata:

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

The initial model had three layers.  The first layer had 80 neurons with the activation function of relu.  The second layer had 30 neurons with the activation function of relu.  The third layer had 1 neuron with the activation function of sigmoid.  The model was trained with 100 epochs.  The accuracy of the original model was 72.83% as shown below.

![Screenshot 2024-08-01 173308](https://github.com/user-attachments/assets/5792d39f-530d-42d8-a2c6-ef734f708e9c)
![Screenshot 2024-08-01 173337](https://github.com/user-attachments/assets/640e35ea-9997-4954-ae2f-814c5f4c7cf8)


This did not meet the target madel performance of 75%.  Several attemps to improve this accuracy by changing the number of epochs, the number of neurons, the activation function, and the number of layers.

When the epochs were increased to 200, the accuracy = 73.04%.  When the number of neurons were increased to 100, 50, 1 (respectively), the accuracy = 72.75%.  However, the best accuracy = 73.06% when the activation function was leaky relu.


## **Summary:** 

From the models attempted, the best accuracy was 73.06% 
![Screenshot 2024-08-01 230158](https://github.com/user-attachments/assets/8ffa6023-f300-4a5f-bbae-d67ab751c841)

Although this is close to the 75% that was trying to be acheived, the model needs to be adjusted further.

