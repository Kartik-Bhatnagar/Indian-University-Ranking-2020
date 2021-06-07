# University-Ranking-2020
Subject: MDSC206
REG no : 20231
Final Project Report On

ALL INDIA , TOP UNIVERSITY RANKINGS 2020

Index

Topic
Introduction
Descriptive Analysis and EDA
Regression
Anova
Manova
LDA
PCA





Introduction : 
The dataset is taken from the kaggle Web site. https://www.kaggle.com/nehaprabhavalkar/indian-universities-rankings-2020.
The Data Basically tells about the Top Universities in India along with their Ranks and Scores in Various Parameters . The Universities in the data consists of 7 Categories. Which are
Architecture
Dental
Engineering
Law
Management 
Medical
Pharmacy



Descriptive Analysis & EDA:
 The data consists of 11 Columns and 460 Rows , altogether making 5060 values in data. The Description of various columns are as following: 
 Institude_id : This is the unique Identification for the Educational Institute in India. This Id is provided by MHRD(ministry of Human Resource Development) of India.
Name:  University Name
tlr : Teaching, Learning & Resources (TLR), Max.Marks(100)

Rpc : Research, Professional Practice & Collaborative Performance (RPC), Max. Marks(100)
Go :Graduation Outcome , Max. Marks(100)

Oi : Outreach and Inclusivity , Max. Marks(100)

Perception : Perception , Max Marks (100)

City : The Name of the City where University is Located.
State: State or Union Territory where the University is Located.
Rank: Rank Scored By the University in the year 2020.
Category: Tells the University category (Architecture, Dental, Engineering, Law, Management, Pharmacy, Medical)

Summary :


Correlation Of Numeric Data


Correlation Plot for All Universities

Inference : 
It is Seen from the Correlation  plot that TLR(Teaching,Learning & Resource) , perception and go (Graduation Outcome) Score are most negatively correlated ,this means that as these scores are increasing the Rank Of the University is Getting Good (Decreasing rank no).

For All Top Ranking Universities altogether :
Correlation,Density and Scatter Plot:

Inference:
This diagram covers three aspects 1)Scatter Plot 2) Density Graphs 3)Correlation 
TLR(Teaching,Learning & Resource) is the most correlated ~= -70 with the rank
Oi Scores are least correlated (~= -50) with the Rank
The order in which the various test scores can affect the rank of the University , according to the correlation plot is : TLR(TeachingLearning resource ),go(Graduation outcome) , perception ,RPC(Research, Professional Practice & Collaborative Performance) , OI (Outreach and inclusivity)



Inference 
The density plots of TLR and OI looking normal
Perception and RPC scores are Skewed leftwards.

Universities in “Architecture” Category






Inference:
Here the tlr score Is the most negatively correlated (-0.85)
And go score is least correlated (-0.38) among all the scoring parameters with respect to the Rank Of universities in architecture category.
For the categories of college in the architecture Tlr score parameter will be the best to estimate the rank of the university 
Universities in “Dental” Category:

Inference
The most correlated parameter is RPC scores(-0.869) and the least correlated parameter(-0.041)  is go scores For the universities in the category of dental .
TLR perception oI Scores are looking normal 

Universities in “Engineering” Category

Inference:
Here the RPC score Is the most negatively correlated (-0.79)
And OI score is least correlated (-0.38) among all the scoring parameters with respect to the Rank Of universities in Engineering category.
For the categories of college in the Engineering Rpc & Tlr score parameter will be the best to estimate the rank of the university .

Universities in “Law” Category


Inference
The most correlated parameter is TLR scores(-0.849) and the least correlated parameter(-0.465)  is perception scores For the universities in the category of Law .
Go, Oi, perception scores will be least helpful in determining the rank of the university in law category.

Universities in “Management” Category:


Inference:
To Determine the Rank in the management category The most correlated scores parameter are RPC and perception .
Tlr and OI parameters are looking normal from the density plot .

Universities in “Medical” Category

Inference
 perception and RPC scores are most correlated to determine the rank Only tlr score is looking normal from the density plot .

Universities in “pharmacy” Category

Inference
 only the RPC score is looking more correlated and all other parameters are very low in correlation. 
Density plots of TLR and go are looking normal.
Number Of Universities Category wise in Top Rankings


Inference 
The category for which the most number of universities are there in top ranking is engineering followed by management then pharmacy then Medical and Dental then law and architecture. 
The most number of universities in the top ranking, almost 200 are from the engineering category .
Universities from category architecture and law equal to 20 .
The number of top universities in category pharmacy and management are 75 each ,which contributes 16% of the universities in the top Ranking respectively.
State wise universities in the top ranking 2020 :

Inference
 the most number of  top universities Are from the state Tamilnadu (66)
Following this order the most number of states with top universities are there is Maharashtra Karnataka Uttar Pradesh Delhi Punjab Telangana and Andhra Pradesh .
States or universities with least number of top universities less than 5 are Pondicherry Chhattisgarh Goa Meghalaya Manipur Bihar Arunachal Pradesh Tripura in Jammu Kashmir .



 REGRESSION:
We have applied the algorithm to find the best parameters to predict the rank Of the university, Results of which are as:

The most significant variables are in Order TLR , GO ,RPC PERCEPTION and OI .

We made 6 models which are as :
Inference:
All these models were trained using train data 
The first model was giving adjusted R squared value around 0.49 and when we reach our 6th model ,The adjusted R squared value we noted is 0.9727 
From all the given above models the model number six was best and adjusted R squared value  coming was 0.9727 .
So we can use model number 6 to predict the  Rank on the test data .
From this sixth model it is inferred that all the models are negatively correlated this means that whenever all the scores are increasing the rank number is decreasing ,Which directly means that the university is having good rank when the scores are more 

CONTOUR Plots of Various parameters with respect to Rank 
Inference:
 all these counter plots are giving partial ellipse which is good For our model.The only exception is coming when the rank is beyond hundred . That maybe because many universities are not having rank more than hundred in the given data set.


Inference:
 The values are almost normal according to the normal QQ Plot, And the residual versus fitted values are looking in a straight line after 50 .

Predicting Rank Of the University in Test Data



ANOVA 

To find the If the Universities Are different in terms of tlr (Teaching learning and resource) scores.

TLR Overview in our dataset:



Inference:
The TLR Data is distributed normally in the dataset containing information about all Categories of Universities.
The average TLR value is coming between 60 to 70 
 

Inference:
This Plot basically  shows all the points depicting TLR scores of various Universities Category wise
The DataPoints for The Engineering Universities are more , and it is Evident in this Diagram and the least is for Architecture And law Universities .


Inference:

In the Total Tlr Scores according to University Category , the Most contribution is from the engineering universities totalling around 12000 ,This is because in our data set the most number of universities are from engineering that is 200 .
Order in which other categories of universities contribute To the total score are pharmacy management dental architecture and law .


Inference:
This Plot shows the Spread of TLR scores According to various Universities Categories
The most TLR score in the number of counts is contributed by engineering and architecture universities .
Architecture and Pharmacy College are contributing the least in TLR scores .


Inference :
According to average TLR Scores , the most contribution Is given by the universities in dental category Followed by management medical law pharmacy architecture and at last Engineering .
Architectural and Pharmacy Colleges seems to have same Average TLR Scores
Dental Colleges are having highest TLR Scores
Engineering Universities are having lowest TLR Scores among all.

Performing Anova:

The null and alternative hypothesis of an ANOVA are: - 
H 0 : The seven categories of Universities are equal in terms of TLR Scores 
 H 1 : Mean is different. We can check normality visually:





Inference :
Both the boxplot and the dotplot show a difference in variance for the tlr Score in different categories of Universities .
This means that at least one category Of university is different in terms of tlr (teaching learning and Research) scores .


Using Leverage Test to test the variance

Inference:
The p-value being smaller than the significance level of 0.05, we reject the null hypothesis, so we accept the
hypothesis that variances are different among different University Categories (p-value = 1.496e-05).

The Mean and Standard Deviation according to various University Category are as following :

ANOVA Inference:
• Given that the p-value is smaller than 0.05, we reject the null hypothesis, so we reject the hypothesis that all means are equal.
• We can conclude that at least one University Category is different than the others in terms of TLR scores (p-value < 2.2e-16)
So from the anova test we conclude that  at least one category Of university is different in terms of tlr (teaching learning and Research) scores .


MANOVA: 
(To find if the University categories are different in terms of all score parameters )



Manova Model:

Result: 

P-value(< 2.2e-16) is very small, so we accept the hypothesis that University Are not same in terms of scores 


Covariance is not normal as P-value is very less (<2.2e-16)
Inference
 A one-way multivariate analysis of variance was being performed to determine the effect of different University Category on the five score determining variables(tlr, rpc, go, oi, perception). There are seven different categories: (Architecture, Dental, Engineering, Law, Management,Medical and Pharmacy.)
From the output above, it can be seen that the five variables(tlr,rpc,go,oi,perception) are highly significantly different among University Category.

Linear discriminant analysis (LDA):
To find the category of university by giving these parameters
(tlr,rpc,go,oi,perception).

To perform LDA we have divided our data into train data and test data ,we will be preparing a model with the train data and we will predict using test data and then you will find the accuracy of our model.

The Density plots of different Scoring parameters according to different categories of University .
Inference:
Universities in the category of Engineering are having more score in OI, perception and go
 Medical universities are having more score  in OI, RPC and go 


The various Box-Plots of different Scores with respect to the different University categories.
Inference:
The go Scores in comparison to other scores are more for Universities 
and RPC Scores are less.
Dental Universities are having the highest tlr (Teaching Learning and Research),go(Graduation Outcome) and rpc(Research, Professional Practice & Collaborative)  scores and engineering colleges are having it least.Which means that in terms of Teaching,Learning ,Research, Professional Practice and Graduation Outcome of Dental Colleges are best and Engineering Colleges are worst in this.
The oi(OutReach Inclusivity)  Scores of Management Universities are more , which means that Students in these Universities are good at presentations, workshops, public talks and lab visits, etc. 
And Engineering Universities are having least OI scores.
Perception Score of Architecture Universities are Most and least is of Engineering Universities.This means that Students  and various people involved with the University from Architecture category are giving more good feedback about their University and Engineering universities are performing worse in this. 


LDA Model

Computing P.C.A



The Two Dimensional Analysis of  LDA and PCA are above 


From our model we determine that we are getting 35% error on Train Data and 30% error on Test Data

Prediction Table:


Inference:
The prediction table is performing quite good on test data, By giving all 5 Scoring Parameters it is determining the Category of University it Belongs.
In case of Architecture Universities out of 6 our Model predicted 3 correctly.
In case of Dental Universities the model is not good, out of  9 our Model predicted only 2 correctly
In case of Engineering Universities out of 52 our Model predicted 46 correctly. Here the Prediction rate is very good.
In case of Law Universities out of 5 our Model predicted 4 correctly, which is quite good.
In case of Management  Universities out of 24 our Model predicted 15 correctly.Fine.
In case of Medical Universities out of 5 our Model predicted 3 correctly.
In the case of Pharmacy Universities our Model Predicted 15 correctly out of 25.

We got 69.8 % accuracy with the lda model to find the category of university by giving these parameters
(tlr,rpc,go,oi,perception)

PCA (Principal component analysis ):

To Reduce the Scores Dimensions from 5 to 2.
And to determine Rankings of University based on PCA Scores.
Correlation Matrix


Covariance Matrix


Eigen Values


P.C.A Scores







First two PC Scores (76%) are Enough to cover the entire data.

P.C.A Graph on individual rows 


P.C.A Graph on Scoring Parameters


OI Scores Contributes more on the the PCA followed by rank than RPC then perception then the and least by go

TOP 10 Universities Based on PC Scores 


NOTE: To view full list of TOP Universities (around 460) then go through this file 

https://docs.google.com/spreadsheets/d/1qufOAf54knJOVGQzxNXs_lbkvC8KbNm13aibJslOzi0/edit?usp=sharing
