# Titanic Data Science Solutions

This notebook walks us through the workflow to solve the competition.

## Workflow Stages
The competition solution workflow goes through seven stages described in the Data Science Solutions book.

1. **Question or problem definition.**
2. **Acquire training and testing data.**
3. **Wrangle, prepare, cleanse the data.**
4. **Analyze, identify patterns, and explore the data.**
5. **Model, predict, and solve the problem.**
6. **Visualize, report, and present the problem-solving steps and final solution.**
7. **Supply or submit the results.**

The workflow indicates the general sequence of how each stage may follow the other. However, there are use cases with exceptions:

- We may combine multiple workflow stages. We may analyze by visualizing data.
- Perform a stage earlier than indicated. We may analyze data before and after wrangling.
- Perform a stage multiple times in our workflow. The visualize stage may be used multiple times.
- Drop a stage altogether. We may not need the supply stage to productize or service enable our dataset for a competition.

## Problem Description
This project highlights my approach to the introductory machine learning competition on the Kaggle website - Titanic: Machine Learning from Disaster.

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such a loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper class.

This project analyzes which people were likely to survive. In particular, tools of machine learning have been used to predict which passengers survived the tragedy.

## File Description
- `titanic_predictor`: Contains python code for predicting survival.
- `solution.csv`: Contains sample output file generated from the algorithm.
- `train.csv`: Contains training data.
- `test.csv`: Contains testing data for making predictions.
- `readme.md`: Guide to this project.

## Workflow Goals
The data science solutions workflow solves for seven major goals:

### Classifying
We may want to classify or categorize our samples. We may also want to understand the implications or correlation of different classes with our solution goal.

### Correlating
One can approach the problem based on available features within the training dataset. Which features within the dataset contribute significantly to our solution goal? Statistically speaking, is there a correlation among a feature and solution goal? As the feature values change, does the solution state change as well, and vice-versa? This can be tested both for numerical and categorical features in the given dataset. We may also want to determine correlation among features other than survival for subsequent goals and workflow stages. Correlating certain features may help in creating, completing, or correcting features.

### Converting
For the modeling stage, one needs to prepare the data. Depending on the choice of model algorithm, one may require all features to be converted to numerical equivalent values. So, for instance, converting text categorical values to numeric values.

### Completing
Data preparation may also require us to estimate any missing values within a feature. Model algorithms may work best when there are no missing values.

### Correcting
We may also analyze the given training dataset for errors or possibly inaccurate values within features and try to correct these values or exclude the samples containing the errors. One way to do this is to detect any outliers among our samples or features. We may also completely discard a feature if it is not contributing to the analysis or may significantly skew the results.

### Creating
Can we create new features based on an existing feature or a set of features, such that the new feature follows the correlation, conversion, and completeness goals?

### Charting
How to select the right visualization plots and charts depending on the nature of the data and the solution goals.
