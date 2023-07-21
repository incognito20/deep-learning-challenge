Neural Network Model

## Overview of the Performance

A nonprofit foundation Alphabet Soup desired a tool that would help select applicants
for funding with the best chance of success for their ventures. These models create a binary 
classiier that is designed to help predict whether applicants will be successful if funded.

Information about each organization was contained in the dataset  as follows:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special considerations for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively


## Results

* Data Preprocessing

  * The EIN and NAME columns were removed since they are not targets or features.
  * IS_SUCCESSFUL is the target variable that the predication is attempting to make.
  * The varianbles that are features are:
    * APPLICATION_TYPE—Alphabet Soup application type
    * AFFILIATION—Affiliated sector of industry
    * CLASSIFICATION—Government organization classification
    * USE_CASE—Use case for funding
    * ORGANIZATION—Organization type
    * STATUS—Active status
    * INCOME_AMT—Income classification
    * SPECIAL_CONSIDERATIONS—Special considerations for application
    * ASK_AMT—Funding amount requested


* Compiling, Training, and Evaluating the Model
  
  Various neurons, layers, and activation functions were used for this neural network 
  model in an attempt to optimize the accuracy of the predictions. Various combinations of relu
  and sigmoid were used as activation functions in all optimization attempts. The number of 
  neurons and epochs was significantly varied in the various attempts in order to find an
  optimal model. In addition, two to five layers were used in the various attempts. In the end, 
  the model was not able to achieve the target model performance of 75%. The aforementioned 
  methods were used in numerous attempts to increase model performance, however, the results 
  rarely exceeded 73%.


## Summary

Overall, the various iterations of the model resulted in results that were less than 75% accurate.
In order to achieve the target accuracy, additional activation functions could be utilized as well
as to continue to experiment with various combinations of epochs, neurons, and layers.