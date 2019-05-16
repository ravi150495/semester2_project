# INTERVIEW ANALYSIS
Analysis done on verbal and non-verbal features of interviewee in the interview.

## Work Done:-

* Done the analysis of frequency of students with the ratings of overall hiring and recommended hiring
* Used classification models, to classify the whether student get the job or not on the basis of Overall rating.
* Done analysis on how interviewer changed his focused on some particular features after giving the feedback

The objective of the project is to do some analysis on interviewee and interview behaviour during interview before and after the interview

## Dependencies:
* Numpy
* Pandas
* Seaborn
* Matplotlib(3.0.2 version)
* sklearn
* Python3

```Here we use MIT Dataset. The research paper followed was ```[Automated Prediction and Analysis of Job Interview Performance](https://ieeexplore.ieee.org/document/7579163/)

## Overview:
To accomplish our objective ,the work is completed in the following steps:-

* 1. Importing the Libraries : 
	
We have import the Libraries for numpy, pandas, Matlplotlib, Seaborn.

* 2. Importing the Dataset :

We have imported the dataset of both before feedback and After feedback in interview 

* 3. Feature Selection :

Input: We have selected 16 features including engaged, speaking rate, No           fillers, Smile,paused etc.

Output: Make a list, if overall rating above 6 then append 1 otherwise 0 in a list.

* 4. Normalisation :

We normalized the input data using Standardisation 

x = the value that is being standardized
m = the mean of the distribution
s = standard deviation of the distribution

* 5.  Splitting The data:

We Split the input and output data into train and test in 70:30 ratio.

* 6. Classification Methods:

a) Logistic Regression: both Solver saga and quasi solver

b) KKN : various variant of knn 

c) SVM: both linear and rbf kernel


* 7. Result analysis   


Classification models
Accuracy(Before feedback)
Accuracy(After feedback)
Logistic Regression(Quasi newton solver)
95.23
100
Logistic Regression(saga solver)
95.23
100
KNN(K= 5 , p=2)
95.23
95.23
KNN(K= 10, p=2)
95.23
90.47
KNN(K= 10 , p=1)
95.23
90.47
SVM (Kernel = Linear, C = 1)
95.23
95.23
SVM ( kernel = Linear, C = 5)
95.23
95.23
SVM ( kernel = rbf ,C = 1)
95.23
90.47
SVM (kernel= rbf ,C = 5)
95.23
100


# Analysis :
Analysis on students 
Participants must have  at least 6 ratings in order to get hired.But there are some other  participants who have above 5.5 ratings points then they can be considered because Hiring depends upon all features there may be chance that these students score very good points in some features and get less points in some features because which there ratings get decreased.  

		


