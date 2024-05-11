## [Project #1: Major League Baseball Strikezone Prediction](https://github.com/etsc9287/Strikezone-Project)

The objective of this project is to predict whether or not a pitch will be thrown in the strikezone based on a variety of factors from before the pitch is airborne. 
If MLB batters and their coaches are aware of the diverse factors influencing whether or not a pitch will be thrown in the strikezone, batters will have a better idea of when to swing and when not to swing.  This project can also assist pitchers in being aware of their pitch predictability.  The process of this project includes the following:

1. Importing and merging [multiple datasets](https://www.kaggle.com/pschale/mlb-pitch-data-20152018) into **Python** from Kaggle.com, representing game data, atbat data, and pitching data.
2. Cleaning and engineering a new dataset with a large number of features that play a role in predicting the binary strikezone flag.
3. Building both a general model and a player-specific model with the **logistic regression** algorithm.
4. Evaulating models with measures such as accuracy score, precision, recall, ROC-AUC curves, and f1.
5. Tuning classification thresholds by both accuracy and practicality.
 

## [Project #2: Analyzing the 2019 Kaggle Data Science Survey to Compare Python and R Users](https://www.kaggle.com/etsc9287/python-vs-r-the-data-science-rivalry)   

The objective of this project is to compare Kaggle.com's Python and R users, including users of both and neither languages, in various areas including demographics, learning sources, career, machine learning, and more.  With the usage of these **analytics**, data science enthusiasts, especially beginners, can determine which language(s) to learn or focus on based on their personal situations.  Alternatively, this analysis can also be used to determine a data science enthusiast's best course of action based on the language(s) they already prefer.  The process of this project includes the following:

1. Importing the [2019 Kaggle Data Science Survey Dataset](https://www.kaggle.com/c/kaggle-survey-2019) into **R** from Kaggle.com.
2. Analyzing univariate distributions of variables involving programming language-related survey questions (the target variable) in order to gain an initial understanding of which language (including libraries) is most popular.
3. Analyzing univariate distributions of variables I will be relating to Python/R usage in order to gain an understanding of the data's balance.
4. Using well-detailed and easily understandable bivariate visualizations to illustrate the relationships between a variety of variables and Python/R usage.
5. Using R Markdown to effectively communicate findings and create a comprehensive report.

**Note:** This project was apart of a Kaggle analytics competition in which participants could choose any topic of focus to analyze from the survey.  My notebook was the 19th most liked in the competition and is currently my top Kaggle project.  My other projects involving Kaggle datasets can be found [here](https://www.kaggle.com/etsc9287/notebooks).

## [Project #3: Analyzing Baseball's Spin Rate Revolution](https://etsc9287.medium.com/analyzing-baseballs-spin-rate-revolution-901e022ba60d)  

In this project, I analyze the evolution of spin rates among MLB pitches over time, exploring any discernible patterns that may raise concerns regarding unfair play, particularly in light of the recent foreign substance scandal that has plagued Major League Baseball.  I posted my analyis as a Medium article which includes:

1. Establishing the problem and explaining why spin rate is important and gaining significant attention in MLB media.
2. Performing exploratory analysis pertaining to spin rate on variables including year, players, and ERA (earned run average).
3. Using a Shapiro-Wilkes normality test to compare the distributions of spin rates across years, given the assumption that spin rates should follow a normal distribution.
4. Using linear regression to determine how much spin rate affects pitcher performance in terms of ERA, answering the question of how pitchers are rewarded for (possibly) using foreign substances.
5. Reporting findings based on the analyses.



