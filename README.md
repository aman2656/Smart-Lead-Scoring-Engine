# Smart-Lead-Scoring-Engine
Analysis on finding potential customers to target for lead generation

# Problem Statement:
Given problem statement is supervised learning binary classification problem. Here we have 18 independent feature and 1 dependent feature. Training data has 39161 observations and 19 features. We used multiple classification model with best one came out as XGboost Classifier with F1 score as 68%.

# Steps Perfomed:
1. Data Preprocessing and EDA-
    a. Analysing Basic Metrics - shape, datatypes, statistics of the dataset.
    b. Non Graphical Analysis - value_counts, unique, nuniquue
    c. Graphical Analysis - HistPlot, KdePlot, Distplot, BoxPlot, BarPlot, CountPlot
    d. Missing Values and Outliers Detection - BoxPlot and Inter Quantile Range
2. Applied Data Science-
    a. Check Distribution
    b. Feature Transformation
    c. Missing Values Imputation
    d. Finding Correlation
    e. CLT and Confidence Interval
3. Modelling-
    Tries various supervsied learning algorithms like logistic, decision trees, random forest, boosting, bagging, etc.
    Best Result was given by xgboost with F1 score of 68%.
4. Performed Feature Selection using Feature_Importance attribute of the above tree classifier.
