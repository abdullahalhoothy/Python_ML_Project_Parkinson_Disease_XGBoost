# Python_ML_Project_Parkinson_Disease_XGBoost

progress

# Detecting Parkinson’s Disease with XGBoost – Objective
To build a model to accurately detect the presence of Parkinson’s disease in an individual.

# Learning 
In this Python machine learning project, using the Python libraries scikit-learn, numpy, pandas, and xgboost,I will build a model using an XGBClassifier. I'll load the data, get the features and labels, scale the features, then split the dataset, build an XGBClassifier, and then calculate the accuracy of our model.

# Outcome
In this Python machine learning project, I learned to detect the presence of Parkinson’s Disease in individuals using various factors. I used an XGBClassifier for this and made use of the sklearn library to prepare the dataset. This gives an accuracy of 94.87%, which is great considering the number of lines of code in this python project.

What is Parkinson’s Disease?
Parkinson’s disease is a progressive disorder of the central nervous system affecting movement and inducing tremors and stiffness. It has 5 stages to it and affects more than 1 million individuals every year in India. This is chronic and has no cure yet. It is a neurodegenerative disorder affecting dopamine-producing neurons in the brain.

What is XGBoost?
XGBoost is a new Machine Learning algorithm designed with speed and performance in mind. XGBoost stands for eXtreme Gradient Boosting and is based on decision trees. In this project, I will import the XGBClassifier from the xgboost library; this is an implementation of the scikit-learn API for XGBoost classification.






Dataset for Python Machine Learning Project
Using the UCI ML Parkinsons dataset for this; you can download it [ ]. The dataset has 24 columns and 195 records and is only 39.7 KB.

Prerequisites
You’ll need to install the following libraries with pip:
pip install numpy pandas sklearn xgboost

Steps for Detecting Parkinson’s Disease with XGBoost
Below are some steps required to practice Python Machine Learning Project –

1. Make necessary imports:

2. Read the data into a DataFrame and get the first 5 records.

3. Get the features and labels from the DataFrame (dataset). The features are all the columns except ‘status’, and the labels are those in the ‘status’ column.

4. The ‘status’ column has values 0 and 1 as labels; let’s get the counts of these labels for both- 0 and 1.
I have 147 ones and 48 zeros in the status column in our dataset.

5. Initialize a MinMaxScaler and scale the features to between -1 and 1 to normalize them. The MinMaxScaler transforms features by scaling them to a given range. The fit_transform() method fits to the data and then transforms it. I don’t need to scale the labels.

6. Now, split the dataset into training and testing sets keeping 20% of the data for testing.

7. Initialize an XGBClassifier and train the model. This classifies using eXtreme Gradient Boosting- using gradient boosting algorithms for modern data science problems. It falls under the category of Ensemble Learning in ML, where I train and predict using many models to produce one superior output.

8. Finally, generate y_pred (predicted values for x_test) and calculate the accuracy for the model. Print it out.

