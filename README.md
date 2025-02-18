# HeartDisease-BinaryClassification
I made this project with a classmate for my 'Machine Learning II' course. 
The objective is to predict whether an individual is likely to have heart disease based on their health data.

There are two Jupyter notebooks. The first one pre-process the data that we download directly from the repository. 
The second one uses two CSV files with the pre-processed data (which we exported, but this step is not included in the code). 
You don’t need to do anything; this information is just in case you don’t understand what we did.

We took the data from "https://archive.ics.uci.edu/dataset/45/heart+disease". The dataset contains data from patients from differents hospitals around the world.
The originall output was multi-class but we binarize to simplify the problem. The data contains information like the age, sex, resting electrocardiograph results,
maximum heart rate achived, etc. 

The target feature indicates whether a person is likely to have heart disease (represented by 1) or not (represented by 0).

This project has two parts (or tasks). In the first one, we use a linear model and a Multi-Layer Perceptron, along with Exploratory Data Analysis (EDA).
In the second part, we use the Support Vector Machine model, testing different kernels to choose the one that best fits our data. 
In both tasks, we perform some feature engineering, mainly using forward and backward selection, as well as ridge and lasso regularization.
