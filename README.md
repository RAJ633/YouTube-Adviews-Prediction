# YouTube-Adviews-Prediction (Internship project)
A Machine Learning Project to predict the Adviews on YouTube based on other features of the video namely likes ,dislikes ,views ,comments , category ,duration .

# CONTEXT
It is known fact that youtube advertisers pay content creaters based on the number of adviews and clicks for the goods and services being marketed , They estimate the adviews based on some of the metrics like comments,likes,dislikes,duration,category,etc.Therefore this situation drives us to train various regression models and choose the best one to predict the number of adviews. 

# About the Project :

## Cleaning of data (training and testing datasets were attached)
Firstly, the data (train + test datasets) were refined and cleaned before feeding them to the model for better results

## Training the model
The various Regression models used in training the model are :
1)Linear Regression model
2)Support Vector Regressor model
3)Decision Tree Regressor model
4)Random Forest Regressor model
5)Artificial Neural Network model

# Result of training  
1)Errors of Linear Regression model:
Mean Absolute Error: 3707.378005824532
Mean Squared Error: 835663131.1210337
Root Mean Squared Error: 28907.83857573986

2)Errors of Support Vector Regressor model:
Mean Absolute Error: 3707.378005824532
Mean Squared Error: 835663131.1210337
Root Mean Squared Error: 28907.83857573986

3)Errors of Decision Tree Regressor model:
Mean Absolute Error: 2619.156420765027
Mean Squared Error: 880790616.1427596
Root Mean Squared Error: 29678.11678902082

4)Errors of Random Forest Regressor model:
Mean Absolute Error: 3326.890133302947
Mean Squared Error: 684207622.2219472
Root Mean Squared Error: 26157.362677111527

5)Errors of Artificial Neural Network model:
Mean Absolute Error: 3304.0037774779107
Mean Squared Error: 829976062.346561
Root Mean Squared Error: 28809.305134740076
 
Based on the above results Decision Tree Regressor model was selected for testing (i.e. for prediction)

The code for training and testing was attached along with prediction results of test dataset

# Thus, prediction of adviews was done successfully using the decision tree Regressor model 
