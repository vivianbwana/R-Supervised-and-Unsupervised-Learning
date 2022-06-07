# R-Supervised-and-Unsupervised-Learning
Application of Supervised and Unsupervised learning  using R-programming 

## Part 1. R-Supervised Learning

### Customer Segmentation Modelling

The aim of this project is to be able to identify customers who are likely to click on the ads and create a classification model for the same.

#### Introduction

A Kenyan entrepreneur has created an online cryptography course and would want to advertise it on her blog. She currently targets audiences originating from various countries. In the past, she ran ads to advertise a related course on the same blog and collected data in the process. She would now like to employ your services as a Data Science Consultant to help her identify which individuals are most likely to click on her ads. 

#### Approach
This is a classification problem where the target varibal is the column "Clicked.on.Ad". It is ver important for any online entreprenuer to be able to identify customers who would click on ads as this will help inform how the ads could be posted on the blog.

For this project, we will apply the following approach:
First, we will perform data cleaning procedures such as removal of missing values, duplicates and features that are not important.
We will then perform univariate, bivariate and multivariate analysis to see how the different features affect our target variables.
Using the insights gathered from the above analysis.

#### Dataset
The dataset used for this project can be found on this link.
http://bit.ly/IPAdvertisingData

#### Technologies applied
R programming language using R markdown.

#### Methodology
We created three different mode algorithmss for this classification process.
These were: Multiple Linear Regression, Decision Tree and Naive Bayes algorithms.




## Part 2. R-Unsupervised Learning

### Customer Clustering

The aim of this project is to be able to randomly group customers by reffering to different customer behaviours so as to identify how such customers visit the different we pages provided.

#### Introduction

As a service provider, it is very important to be able to identify the general overview of how your characters behave. In order to be able to cluster.  customers based on their behaviours.
Kira Plastinina (Links to an external site.) is a Russian brand that is sold through a defunct chain of retail stores in Russia, Ukraine, Kazakhstan, Belarus, China, Philippines, and Armenia. The brand’s Sales and Marketing team would like to understand their customer’s behavior from data that they have collected over the past year. More specifically, they would like to learn the characteristics of customer groups.

#### Approach
The following approach was applied:
First, we will perform data cleaning procedures such as removal of missing values, duplicates and any anomalies.
We will then apply Exploratory Data Analysis such as univariate, bivariate and multivariate analysis to see the characteristics of the different features of our dataset.
Using the insights gathered from the above analysis, we would then create clusters using K-Means and Heirarchical clustering techniques.

#### Dataset
The dataset used for this project can be found on this link.
http://bit.ly/EcommerceCustomersDataset

##### Dataset Description
The dataset consists of 10 numerical and 8 categorical attributes. The 'Revenue' attribute can be used as the class label.
"Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represents the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real-time when a user takes an action, e.g. moving from one page to another. 
The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 
The value of the "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. 
The value of the "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that was the last in the session.
The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 
The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with the transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 
The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.


#### Technologies applied
R programming language using R markdown.

#### Methodology
We created three different clusters using two different cluster creation techniques for this process.
These were: K-Means and Heirarchical clustering techniques.
The optimal number of clusters i.e the k value, was arrived at by applying the Elbow and Silhoutte k-cluster optimization techniques. 
