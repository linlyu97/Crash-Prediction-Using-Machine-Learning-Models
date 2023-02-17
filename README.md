# Crash-Prediction-Using-Machine-Learning-Models

### Purpose of project
First of all, recent studies on crashes severity modeling are reviewed, showing that most of them employ imbalanced datasets to train MLAs. 

Secondly, the project will do exploratory data analysis and recognize key factors that affect crash severity most. 

Next, in order to handle imbalanced crashes datasets and provide a better prediction for the minority class, the random under-sampling the majority class (RUMC) technique is used for minor classes. The project also implemented random over-sampling the majority classes (ROMC) and tried different sample distribution combinations to under sample minor classes while over sample the majority in order to improve the prediction accuracy for testing datasets. 

Four machine learning algorithms would be used in this project: K-Nearest Neighbor (KNN), Logistic Regression (LR), Decision Tree and Random Forest (RF). Furthermore, with a goal of showing that RUMC and ROMC are useful in defining non-weak classifiers in predicting the minority class, the project provides a comparison between two scenarios. One scenario is training the four machine learning algorithms on imbalanced training dataset. Another scenario is training four machine learning algorithms on balanced training set with the use of a RUMC-ROMC based method. The project will calculate and compare the performance of different classifiers on different metrics: accuracy, true positive rate (recall), false positive rate, true negative rate, precision, F1-score, and the confusion matrix.

### Materials
severity-prediction-in-sfo-bay-areasipynb.ipynb contains the code and data source link. 

final_report.pdf contains the literature review, methods, results and analysis.
