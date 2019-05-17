# INTERVIEW ANALYSIS
Analysis done on verbal and non-verbal features of interviewee in the interview.

## Work Done:-

* Done the analysis of frequency of students with the ratings of overall hiring and recommended hiring
* Used classification models, to classify the whether student get the job or not on the basis of Overall rating.
* Done analysis on how interviewer changed his focused on some particular features after giving the feedback

The objective of the project is to do some analysis on interviewee and interviewer behaviour during interview before and after the interview

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

![accuracy](https://github.com/ravi150495/semester2_project/blob/master/result1.png)


# Analysis :

`Analysis on students`

`No of participants vs Ratings in Interview before taking Feedback (Frequency Vs Ratings):`

![](https://github.com/ravi150495/semester2_project/blob/master/Before_f.png)

`Participants must have  at least 6 ratings in order to get hired.But there are some other  participants who have above 5.5 ratings points then they can be considered because Hiring depends upon all features there may be chance that these students score very good points in some features and get less points in some features because which there ratings get decreased.`

` Participants After taking Feedback in interview(Frequency Vs Ratings): `

![](https://github.com/ravi150495/semester2_project/blob/master/After_f.png)

`Analysis on How interviewer changed his focused after giving feedback `		

![](https://github.com/ravi150495/semester2_project/blob/master/Interviewer.png)

`We found that after giving feedback to the students about their weakness. Next time during Interview , Interviewer focused on those features which were weak earlier. As we have seen , Features like Engaged, Smiled , Excited, Speaking rate, No fillers, Friendly, Paused, Engaged tone get increased which means In overall hiring the importance of these features get increased.
`
