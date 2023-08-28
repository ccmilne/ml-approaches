# ML References

Collection of ML use-cases, implementations, and cleaned datasets for reference. Scripts are sourced from personal projects and coursework.

## Folder Structure

Directories are grouped by ML Libraries + Coursework examples

```bash
|--PyTorch
|   |-- LogIt implementation
|
|--Keras
|   |-- Computer Vision with CNN
|
|--HuggingFace (Transformers)
|   |-- Predicting Helpful StackOverflow Answers
|
|--Scikit-Learn
|
|--Coursework
|   |--SI630 - Natural Language Processing
|   |--SI670 - Applied Machine Learning
|   |--SI671 - Data Mining
```


## Use-Cases (excluding Neural Net Approaches)

_Project focus (dataset: methods and topics)_

- ### Supervised Learning
    - #### Regression Models (_Linear_, _Logistic_, _Ridge_, _Lasso_)
        - [Breast Cancer prediction](https://github.com/ccmilne/ml-approaches/blob/main/courswork/SI670/assignments/si670f21_hw_4.ipynb) (Wisconsin Diagnostic Database: Linear Regression, Lasso, Ridge, GridSearchCV)
        - [Fraud detection](https://github.com/ccmilne/ml-approaches/blob/main/courswork/SI670/assignments/si670f21_hw_3.ipynb) (Logistic Regression, Precision/Recall, ROC Curves)
        - [Housing prices prediction](https://github.com/ccmilne/ml-approaches/blob/main/courswork/SI670/assignments/si670f21_hw_5.ipynb) (Boston Housing: K-Fold, Ridge)
        - [Amazon product rating predictions](https://github.com/ccmilne/ml-approaches/blob/main/courswork/si671/hw3/hw3.ipynb) (Amazon co-purchasing network: NetworkX, Linear, SVC, LogIt)
    - #### Tree-Based Models (_Decision Tree_, _Random Forests_, _Gradient Boosting Regression_, _XGBoost_, _LightGBM Regressor_)
        - [Credit Risk](https://github.com/ccmilne/ml-approaches/blob/main/courswork/SI670/assignments/si670f21_hw_5.ipynb) (Statlog German Credit Data: Decision Tree, Random Forest)
- ### Unsupervised Learning
    - #### Clustering (_K-Means_, _Hierarchical Clustering_, _Gaussian Mixture Models_)
    - #### Association (_Apriori algorithm_)
        - [Evaluating frequent itemsets](https://github.com/ccmilne/ml-approaches/blob/main/courswork/si671/hw1/hw1.ipynb) (Twitter emojis 10K: Apriori)

- ### Other
    - #### Time Series
    - #### NLP
