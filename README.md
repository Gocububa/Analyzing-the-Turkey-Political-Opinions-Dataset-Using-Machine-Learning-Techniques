# Analyzing-the-Turkey-Political-Opinions-Dataset-Using-Machine-Learning-Techniques

This repository contains the code and results of an analysis of the Turkey Political Opinions Dataset (Kaggle Link: https://www.kaggle.com/datasets/yemregundogmus/turkey-political-opinions/data)

The primary objective of this study is to:
**Identify trends in political orientation** within the Turkish population based on the collected data.
**Investigate the challenges posed by imbalanced data** in political opinion analysis.
**Evaluate the performance of various machine learning models** in predicting political orientations.

**Methodology**

1. **Data Preprocessing:**
    * Handled class imbalance using the SMOTEN (Synthetic Minority Over-sampling Technique for Nominal Data) method.
    * Normalized demographic features where necessary.
2. **Model Training:**
    * Employed a variety of machine learning classifiers, including:
        * Support Vector Machine (SVM)
        * Random Forest
        * k-Nearest Neighbors (KNN)
        * Logistic Regression
        * XGBoost
        * AdaBoost
        * Neural Network
        * LightGBM
        * Stacking Classifier
    * Performed hyperparameter optimization using Grid Search Cross-Validation.
3. **Evaluation:**
    * Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.

**Results**

* Achieved an accuracy range of 40-50% across all models, indicating the dataset's limitations and potential challenges in predicting political opinions.
* The Stacking Classifier demonstrated the best performance, suggesting that combining multiple models can improve predictive accuracy.
* Observed varying performance across different models, highlighting the importance of careful model selection for this specific task.

**Conclusions**

* Data quality and class imbalance significantly impacted model performance.
* Feature engineering and more sophisticated data preprocessing techniques are crucial for improving accuracy.
* Ensemble methods, such as the Stacking Classifier, showed promise in capturing complex patterns in the data.
