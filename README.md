# InternetUsageDataAnalytics


Introduction 
The objective of this project is to analyze the demographic information of Internet users with both clustering techniques as well as classification techniques.
From Unsupervised techniques optimal clusters are identified for Internet users.
Then supervised methods are used to classify these 2 cluster users as Novice Internet users and Expert users with goal to perform Customer segmentation.


Dataset Description
The dataset is collected from UCI website link as follows: https://archive.ics.uci.edu/ml/datasets/Internet+Usage+Data 


This data comes from a survey conducted by the Graphics and Visualization Unit at Georgia Tech October 10 to November 16, 1997. The subset of the survey provided is this "general demographics" of internet users. The data have been recorded as entirely numeric, with an index to the codes described in the "Coding" file.

It is a demographics of internet usage dataset of 1.5M uncompressed size. This dataset includes 10104 rows and 72 feature variables. Each row corresponds to an internet user, and includes many other variables like Education level, Gender, Age, Location, Income etc.
Rows: 10104 Columns: 72
These 72 columns are about age, gender, race etc. of internet users and their values are encoded in numeric data. Out of these 72 columns 14 are selected for building clustering models and perform segmentation of Internet users. The dataset does not contain target variable, thus unsupervised methods are employed.

In this repository the deatiled exploration of Internet usage data is proposed for classifying internet users using both supervised and unsupervised learning.
