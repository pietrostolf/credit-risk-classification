# credit-risk-classification
credit-risk-classification challenge files go here

Notebook file "credit_risk_classification.ipynb" is located inside the "Credit_Risk" folder. Data file "lending_data.csv" is at "Credit_Risk/Resources".

Overview of the Analysis

The purpose of this analysis was to develop machine learning models to predict the risk level of loans based on financial information. The dataset provided contained various financial features related to loans, and the objective was to predict whether a loan is classified as "healthy" (class 0) or "high-risk" (class 1).

The variables to be predicted were the loan risk levels.

The analysis involved the following stages of the machine learning process:

    Data preprocessing: Cleaning and preparing the dataset for model training.
    Feature selection: Identifying relevant features that contribute to loan risk prediction.
    Model training: Utilizing machine learning algorithms, particularly logistic regression, to build predictive models.
    Model evaluation: Assessing the performance of the models using metrics such as accuracy, precision, and recall.

Additionally, to address the class imbalance issue in the dataset, oversampling techniques were employed.
Results

    Machine Learning Model 1:
        Balanced Accuracy: 0.944
        Precision (Class 0): 1.00
        Recall (Class 0): 1.00
        F1-Score (Class 0): 1.00
        Precision (Class 1): 0.87
        Recall (Class 1): 0.89
        F1-Score (Class 1): 0.88

    Machine Learning Model 2 (Trained with Oversampled Data):
        Balanced Accuracy: 0.995
        Precision (Class 0): 1.00
        Recall (Class 0): 1.00
        F1-Score (Class 0): 1.00
        Precision (Class 1): 0.87
        Recall (Class 1): 1.00
        F1-Score (Class 1): 0.93

Summary

Based on the results, Machine Learning Model 2, which was trained with oversampled data, performs better than Model 1 trained on the original data. Model 2 exhibits higher accuracy, precision, and recall for predicting both healthy loans (class 0) and high-risk loans (class 1). The use of oversampling addresses the class imbalance issue, resulting in improved performance and a higher ability to identify high-risk loans.

The choice of the best-performing model depends on the specific problem and the importance of different metrics. If correctly identifying high-risk loans (class 1) is of utmost importance, Model 2 with its higher recall score for class 1 is the recommended choice. However, if a balance between class 0 and class 1 predictions is crucial, Model 1 still performs well overall.

