# Heart-Disease-Prediction



### Why Heart-Disease-Prediction?
The correct prediction of heart disease can prevent life threats, and incorrect prediction can prove to be fatal at the same time. Heart disease describes a range of conditions that affect your heart. Today, cardiovascular diseases are the leading cause of death worldwide with 17.9 million deaths annually, as per the World Health Organization reports. Various unhealthy activities are the reason for the increase in the risk of heart disease like high cholesterol, obesity, increase in triglycerides levels, hypertension, etc.But as time is passing, a lot of research data and patients records of hospitals are available. There are many open sources for accessing the patient’s records and researches can be conducted so that various computer technologies could be used for doing the correct diagnosis of the patients and detect this disease to stop it from becoming fatal. In machine learning, a common problem is the high dimensionality of the data; the datasets which we use contain huge data and sometimes we cannot view that data even in 3D, which is also called the curse of dimensionality

## A Walkthrough

### Obtain heart data set

### Data Preprocessing
The obtained raw data is fed into our machine. To make it fit and compatible for Machine Learning.

### Train Test Split
Split the data into training data and testing data. This is because we have to train the Machine Learning algorithm using training data and we will evaluate the model using testing data

### Logistic Regression Model
We use binary classification in which we use 0 and 1 to predict if the patient has heart disease or not. Logistic Regression is a great method to achieve this. Logistic regression is a process of modeling the probability of a discrete outcome given an input variable.

### Trained Logistic Regression Model
Through the given data we can get a trained logistic regression model and when we feed our data we can find out if our patient is a heart disease patient or not.

## Obtaining Dataset

The Dataset for heartprediction is obtained from Kaggle. We have 14 columns containing age, gender, sex, chest pain type, resting blood pressure, serum cholestrol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise induced angina, old peak,slope of the peak exercise ST segment, number of major vessels etc.

I am using google collab

Upload the Dataset
Import the Dependencies (numpy, pandas, train_test_split, LogistiRegression model, accuracy_score)
load a csv data to pandas dataframe (reads csv data in panda Dataframe)
check the number or rows and colums (Lets see how much Data we have!!)
use heart_data.info()  to obatin more data
check the missing values
Obtain stastical measure of Data
Check the target of the dataframe
Give values to your binary (1 --> Defective, 0 --> Healthy)
Take 2 variables (x and y) in whuch y has the target and x has the features
Split the features and the targets
Split into train data and test data
Train the machine learning model using logistic regression model using model.fit()
Now Evalute the model using accuracy score for training and testing data.
The predicted value is cross checked with accuracy_score.
Build a predictive system and add input data ad numpy array


Shoutout to all the youtubers and google for helping me with the project!!!

