# Summer-2022-Internship-Documentation-and-Resources


This will be a documentation record of my progress of my research internship with the Computational Biomedicine deparment at Cedars-Sinai. This internship is focused on improving an AutoML model called 'STREAMLINE' where I would specifically be working on feature selection algorithms involved in creating/improving AutoML and possibly other smaller projects. This will serve for the next person who may have the wonderful opportunity to continue with the ongoing research.

This first small project focuses on using SHAP/Shapley values to explain the magnitude (impact) and significance of feature values in predictions made by the ML. To clarify, SHAP/Shapley values is one of many feature selection algorithms that are meant to help explain the process in making predictions and this algorithm in particular, serves to understand the contribution of each feature value to the difference between the ACTUAL PREDICTION and the AVERAGE (MEAN) PREDICTION. In other words, we are looking for changes/differences in the predicted values of features from the average prediction of ALL features. An easier way of thinking about this is how much each player in a game is contributing  where the player is the "feature" and the payout is the "prediction". Shapley values shed light on the concept of 'fairness' which is especially important if we want to know just how much each feature is individually contributing to the prediction itself.  Some things to consider are:
*Shapley values follow the ASSUMPTION that each feature is independent and will not provide accurate values if two or more features are highly-correlated (highly-correlated features must be removed when selecting features)
*It is NOT the difference of the predicted value after removing the feature from the modeling training
*Long computational time
*Remember...relationships between features are NOT CAUSAL, we look for correlation between features
*

**Projects:**
  1) Feature Selection: Shapley values/SHAP
  

**Learning Resources:**
  * Learning Classifier Systems in a Nutshell (https://www.youtube.com/watch?v=CRge_cZ2cJc)
  * Machine Learning Classifiers - The Algorithms & How They Work (https://monkeylearn.com/blog/what-is-a-classifier/)
  * AUC-ROC Curve in Machine Learning Clearly Explained (https://www.analyticsvidhya.com/blog/2020/06/auc-roc-curve-machine-learning/)
  * 8.5 Permutation Feature Importance (https://christophm.github.io/interpretable-ml-book/feature-importance.html#feature-importance)
  * Machine Learning Explainability using Permutation Importance (https://www.geeksforgeeks.org/machine-learning-explainability-using-permutation-importance/)
  * ML Interpretability: LIME and SHAP in prose and code (https://blog.cloudera.com/ml-interpretability-lime-and-shap-in-prose-and-code/)
  * Stop Permuting Features (https://towardsdatascience.com/stop-permuting-features-c1412e31b63f)
  
  **Shapley Values/SHAP**
  * Welcome to the Documentation of SHAP (https://shap.readthedocs.io/en/latest/index.html)
  * Understanding Shapley Values (https://www.kaggle.com/code/iamleonie/understanding-shapley-values/notebook)
  * Interpretable ML: Shapley Values (https://christophm.github.io/interpretable-ml-book/shapley.html#shapley)
  * Shapley Values - A Gentle Introduction (https://h2o.ai/blog/shapley-values-a-gentle-introduction/)
  * Interpretable Machine Learning using SHAP — theory and applications (https://towardsdatascience.com/interpretable-machine-learning-using-shap-theory-and-applications-26c12f7a7f1a)
  * SHAP for Feature Selection and HyperParameter Tuning (https://towardsdatascience.com/shap-for-feature-selection-and-hyperparameter-tuning-a330ec0ea104#:~:text=SHAP%20helps%20when%20we%20perform,with%20the%20highest%20shapley%20values.)
  * Shapley Value Calculation in Python (https://linuxtut.com/en/4cb3fb64e487dba61b15/
  * Explain Your Model Predictions with Shapley Values (https://www.kaggle.com/code/prashant111/explain-your-model-predictions-with-shapley-values/notebook)
  * How to interpret and explain your machine learning models using SHAP values (https://m.mage.ai/how-to-interpret-and-explain-your-machine-learning-models-using-shap-values-471c2635b78e)
    
        
  **Peer-Reviewed Journals**
  * Explaining individual predictions when features are dependent: More accurate approximations to Shapley value (https://www.sciencedirect.com/science/article/pii/S0004370221000539// doi: https://doi.org/10.1016/j.artint.2021.103502)
