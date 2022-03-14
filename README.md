# Neural_Network_Charity_Analysis   
## Overview   
For this challenge, utilizing Neural Networks and Deep Learning Models via TensorFlow and Pandas libraries in a Python environment to prepare the dataset and create binary classifier to predict outcomes in risk analysis.   
Specifically we are trying to predict the risk of donation groups in terms of utilizing donated funds for the charities they are trying to help fund.   

## Results   
### Data Preprocessing   
* Removed the EIN and NAME columns, they add no value to the machine learning model.   
* Binned APPLICATION_TYPE and group the unique value with less than 500 records as OTHER.   
* Set the target variable as IS_SUCCESSFUL
* Added the remaining 43 variables as "features."   
### Compiling, Training, and Evaluating the Model   
* Our model had 5981 parameters from a result of 43 inputs through 2 hidden layers and a single output layer.   
* Aiming for an accuracy of > 75%, this model was only able to achieve 72.39%. With a little more time and testing out other optimization profiles we may be able to achieve such accuracy.  

![pic](https://github.com/ajsadowy/Neural_Network_Charity_Analysis/blob/main/IMAGES/Evaluate%20Model.png)    

## Summary   
Ultimately the process of machine learning is very quick with the right hardward and only requiring a limited ammount of code makes testing differenct sets of neural networks easy and user friendly.
