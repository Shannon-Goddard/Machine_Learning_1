![Header](/pics/header.png)

#### Table of Contents

[Project Overview](#project-overview)  
[Resources](#resources)  
[Objectives](#objectives)  
[Summary](#summary)   
[Challenge Overview](#challenge-overview)  
[Challenge Objectives](#challenge-objectives)  
[Challenge Summary](#challenge-summary)  
[Colab Link](#colab-link)

## Project Overview  
In 2019, more than 19 million Americans had at least one unsecured personal loan. That’s a record-breaking number! Personal lending is growing faster than credit card, auto, mortgage, and even student debt. With such incredible growth, FinTech firms are storming ahead of traditional loan processes. By using the latest machine learning techniques, these FinTech firms can continuously analyze large amounts of data and predict trends to optimize lending.  

In this module, we used Python to build and evaluate several machine learning models to predict credit risk. Being able to predict credit risk with machine learning algorithms can help banks and financial institutions predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud. 

## Resources
- **Data Source:** []()
- **Software:** Python and Scikit-learn  

## Objectives  
- Explain how a machine learning algorithm is used in data analytics.
- Create training and test groups from a given data set.
- Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Compare the advantages and disadvantages of each supervised learning algorithm.
- Determine which supervised learning algorithm is best used for a given data set or scenario.
- Use ensemble and resampling techniques to improve model performance.

## Summary  
### Explain how a machine learning algorithm is used in data analytics.
### Create training and test groups from a given data set.
### Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
### Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
### Compare the advantages and disadvantages of each supervised learning algorithm.
### Determine which supervised learning algorithm is best used for a given data set or scenario.
### Use ensemble and resampling techniques to improve model performance. 

## Challenge Overview  
In this challenge, we built and evaluated several machine learning models to assess credit risk, using data from LendingClub; a peer-to-peer lending services company.  

Credit risk is an inherently unbalanced classification problem, as the number of good loans easily outnumber the number of risky loans. Therefore, we employed different techniques to train and evaluate models with unbalanced classes. We used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Our final task was to evaluate the performance of these models and made a recommendation on whether they should be used to predict credit risk.  
  
## Challenge Objectives  
- Implement machine learning models.
- Use resampling to attempt to address class imbalance.
- Evaluate the performance of machine learning models.

## Challenge Summary  
#### Instructions
You’ll use the imbalanced-learn library to resample the data and build and evaluate logistic regression classifiers using the resampled data. Download the files you’ll need, which include starter code and the dataset:  

Download Module -17-Challenge-Resources.zip  

You will:
1. Oversample the data using the RandomOverSampler and SMOTE algorithms.
2. Undersample the data using the cluster centroids algorithm.
3. Use a combination approach with the SMOTEENN algorithm.  

For each of the above, you’ll:  

1. Train a logistic regression classifier (from Scikit-learn) using the resampled data.
2. Calculate the balanced accuracy score using balanced_accuracy_score from sklearn.metrics.
3. Generate a confusion_matrix.
4. Print the classification report (classification_report_imbalanced from imblearn.metrics).  

Lastly, you’ll write a brief summary and analysis of the models’ performance. Describe the precision and recall scores, as well as the balanced accuracy score. Additionally, include a final recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.  

#### Extension
For the extension, you’ll train and compare two different ensemble classifiers to predict loan risk and evaluate each model. Note that you’ll use the following modules, which you have not used before. They are very similar to ones you’ve seen: BalancedRandomForestClassifier and EasyEnsembleClassifier, both from imblearn.ensemble. These modules combine resampling and model training into a single step. Consult the following documentation for more details:
- [Section 5.1.2. Forest of randomized trees](https://imbalanced-learn.readthedocs.io/en/stable/ensemble.html#forest)
- [imblearn.ensemble.EasyEnsembleClassifier](https://imbalanced-learn.readthedocs.io/en/stable/generated/imblearn.ensemble.EasyEnsembleClassifier.html)  

Use 100 estimators for both classifiers, and complete the following steps for each model:  

1. Train the model and generate predictions.
2. Calculate the balanced accuracy score.
3. Generate a confusion matrix.
4. Print the classification report (classification_report_imbalanced from imblearn.metrics).
5. For the BalancedRandomForestClassifier, print the feature importance, sorted in descending order (from most to least important feature), along with the feature score.  

Lastly, you’ll write a brief summary and analysis of the models’ performance. Describe the precision and recall scores, as well as the balanced accuracy score. Additionally, include a final recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.  

#### Submission
Host your challenge assignment on GitHub, including:
- Your Jupyter Notebook file(s) with your code and analysis.
- Your dataset.
- A README.md file describing your project.
