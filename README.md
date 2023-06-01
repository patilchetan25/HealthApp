
# Health Application

It's a multiple machine learning application of disease prediction
 
 * Diabetes Prediction
 * Heart Disease Prediction
 * Parkinson's Disease Prediction

 ## Approach

* Gathering the Data: Data preparation is the primary step for any machine learning problem. We will be using a dataset from Kaggle for this problem. This dataset consists of two CSV files one for training and one for testing. 

* Cleaning the Data: Cleaning is the most important step in a machine learning project. The quality of our data determines the quality of our machine-learning model. So it is always necessary to clean the data before feeding it to the model for training. In our dataset all the columns are numerical, the target column i.e. prognosis is a string type and is encoded to numerical form using a label encoder.

* Model Building: After gathering and cleaning the data, the data is ready and can be used to train a machine learning model. We will be using this cleaned data to train the Support Vector Classifier, Naive Bayes Classifier, and Random Forest Classifier. We will be using a confusion matrix to determine the quality of the models.

* Inference: After training the three models we will be predicting the disease for the input symptoms by combining the predictions of all three models. This makes our overall prediction more robust and accurate.

## Demo 


![ezgif com-video-to-gif](https://github.com/patilchetan25/HealthApp/assets/88223249/0f9e8275-b15a-47ca-b25d-640e100124b2)


## Link :point_down:
[Health App](https://patilchetan25-healthapp-multiple-disease-pred-okcr7y.streamlit.app/)
