**Name:** Ozgur Polat
# **Data Set: House Prices: Advanced Regression Techniques**
## **Predict sales prices and practice feature engineering, RFs, and gradient boosting**
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this Kaggle competition data set challenges you to predict the final price of each home.

![alt text](https://docs.google.com/uc?export=download&id=1CrVuFQEYVKPdh2qpylSRwAozRJpKZi_-)

**Research question:** What interesting factors other than the obvious factors such as the location or the age of the house play a role in determining the ultimate price of a house.

**Summary:** I performed an exploratory data analysis on this set. Since it is a rich data set with 81 columns, first I devided the features into four diffrent data frames based on what kind of values they contain such as numerical or categorical etc. Then I looked at missing values. I also performed correlation analysis between various features and checked to see if the features are normally distributed. I also fitted PDF curves and performed goodness of fit analysis, which is something we learned during the lectures.

Finally I looked at various features and made many observations. here are some examples: I looked at number of houses sold in each month throughout the year by plotting a histogram and checked to see if this correlates with average monthly temperatures in Ames, Iowa. I also checked how they compare with monthly median house sale prices. I discovered that having a fireplace can increase the value of a house significantly. I also discovered that having a fence made from good matarial does not really influence the sale price significantly but a fence that provides greater privacy does. I discovered that sale price rate of increase is quite different for houses with one full bathroom and for houses with two full bathroom.

**What is learned about the data:** What I really learned about this data set was that ultimate sale price of a house is complex and many different factors can play role.

**What is learned from the data about the world:** If I can give the fireplace feature as an example. I remembered what my mother told me about fireplaces. She said that they increase the value of a house more than you spend for building them. This observation was valid for Turkey, and it was interesting to find out that it is also valid for US. So perhaps there is something universal about fireplaces.

**Data Source:** https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview

The [Ames Housing dataset](http://jse.amstat.org/v19n3/decock.pdf) was compiled by Dean De Cock for use in data science education. It's an alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

<img src="https://docs.google.com/uc?export=download&id=1SRMCosR-yPQwZVuNOmp1oo0_QzHDztyw" style="width:552px;height392px"/>

**Motivation:** My main motivation for selecting this data set is the richness of this data set which has 81 features. This is an ongoing machine learning competition at Kaggle which I would like to eventually participate. For the current project I only want to use this data set for exploratory data analysis. However, after ReDi training, I would like to continue working with this data set, and eventually build a machine learning model and join the Kaggle competition. The data set is also interesting for me, because I would like to own a house one day and it would be interesting to know what kind of factors play role in determining the price of a house other than the obvious ones such as location or the year it was built, etc.

# Table of Contents
# 1. Explotoring the Dataset
## 1.1 Description of Data (Type, Scale, Size, etc.)
## 1.2 Analysis of Missing Values
## 1.3 Statistical Analysis
### 1.3.1 Summary Statistics
### 1.3.2 Multicollinearity (Highly correlated features)
#### 1.3.2.1 Violin Plots
#### 1.3.2.2 Box Plots
#### 1.3.2.3 Swarm Plots
#### 1.3.2.4 Correlation Plots
#### 1.3.2.5 Heat Map with Pearson Correlation Values
### 1.3.3. Multivariate Normality
#### 1.3.3.1 Statistical summary of 'SalePrice' distribution
#### 1.3.3.2 Histogram of Target Feature 'SalePrice'
#### 1.3.1.3 Histograms of Independent features
#### 1.3.3.4 Applying Log Transformations to Features
#### 1.3.3.5 Fitting a Probability Density Function to 'SalePrice' and Finding the best Fit (Goodness of Fit)
## 1.4. Analysis of Categorical Features
### 1.4.1. Nominal Categorical Features
### 1.4.2. Ordinal Categorical Features
## 1.5 Numerical Discreet Features
# 2. Results and Discussion
