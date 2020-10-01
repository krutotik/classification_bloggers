# BLOGGER Data Set Classification 

## Problem description

In this report we have binary classification problem to solve. We want to classify if a blogger is a professional or not based on other parameters of a person, which will be listed later.

The Dataset can be found here:

* https://archive.ics.uci.edu/ml/datasets/BLOGGER

## Data set information

In this paper, authors look for to recognize the causes of users tend to cyber space in Kohkiloye and Boyer Ahmad Province in Iran. Collecting information to form database is done by questionnaire. This questionnaire is provided as oral, written and also programming of a website which includes an internet questionnaire and the users can answer the questions as they wish. They entered their used websites, blogs and social networks during the day. After collecting questionnaires, the wed addresses are gathered to get expected results. And finally, their trustfulness is checked by analyzing their used web pages. As the results were same, for getting better and noiseless response, they will put in database. 

Then this information is used to predict future tendency anticipation of users to blogging. In order to get correct answer for their paper, authors classify bloggers to two
groups: professional bloggers and seasonal (temporary)
bloggers. Professional bloggers are those who adopt blog as
an effective digital media and interested in digital writing in
continuous time intervals. Seasonal (temporary) bloggers
are not professionals and follow blogging in discrete time
periods. 

##  Target variable and features explanation

The noisy or too detailed data in database made authors far from to get proper and suitable answers of algorithms. That is why the dataset was preprocessed and some non-relevant data was eliminated before the dataset was published.

Authors of the paper considered following parameters as questions. Those parameters will be used as features for the model that will be created in this report:

* education (high, medium, low);
* political caprice (left, middle, right); 
* topics of the blog (impression, political, tourism, news, scientific);
* local media turnover (yes or no);
* local, political and social space (yes or no);



The following parameter is considered as target variable for the model:

* professional blogger (yes or no)

## Steps
* Feature Distribution Analysis
* Data preprocessing for future exploration
* Exploratory Data Analysis
* Modeling and hyperparameter tuning
* Accuracy, Precision, Recall, and f1 calculations
* ROC Curve and AUC score 
* Model comparison 

## Screenshots
### Feature Distribution Analysis
![Feature distribution](images/feature_distributions.png?raw=true "name_1")
### Visualization of the relationships between features and target variable
![Features and target variable](images/features_and_target_variable.png?raw=true "name_2")
### Feature Correlation
![Feature correlation](images/feature_correlations.png?raw=true "name_3")
### Results from Machine Learning Algorithms
F1 scores:

![F1_score](images/F1_score.png?raw=true "name_4")
### ROC curve
![ROC Curve](images/ROC_curve.png?raw=true "name_5")

AUC scores:

![AUC score](images/AUC_score.png?raw=true "name_6")
