# Credit-Card-Fraud-Analysis

### The main aim of this project is to detect credit card risk using machine learning techniques. We know that there are loads of fraud techniques happening in the banking sector. Machine Learning methods are of two types of techniques such as supervised and unsupervised. Here we will apply AdaBoost and Decision tree for the same data and predicting the credit risk. The accuracy rate of both the machine learning techniques is analyzed and then the result is obtained.


## Major Steps followed during the project

### 1. Data Gathering

Dataset has been downloaded from kaggle. The dataset consist of 1001 rows and 21 columns. In this dataset, the class column has two values 0 and 1 in which 0 indicates that particular case is not fraud and 1 indicate that particular case is fraud.

### 2.Feature Engineering:

The missing values should be checked in the dataset and removed. 

Also, perform exploratory data analysis to analyze the data with the help of seaborn library which is used for data visualization from which I came to know that the count of no. of fraud cases (492) is very less as compared to non-fraud cases (284315).
So, we can conclude that the given dataset is imbalanced.

Now, our dataset is ready for applying to any machine learning algorithm.

### 3.Model Training:

I have divided the dataset into train and test using the train_test_split method of sklearn library.

For training the dataset, I have used two classification algorithms Decision Tree and AdaBoost. Although, the dataset is imbalanced, but we need not to handle the imbalanced dataset as these two classification algorithm will take care of the imbalanced dataset.

Since, only accuracy doesn’t tells that how good our model is. So, we have to calculate other performance metrics such as precision, recall, support. These performance metrics can be calculated with the help of classification report.
A classification report is used to measure the quality of predictions from a classification algorithm.

