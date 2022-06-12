# Explainable Heart Disease Prediction Using Ensemble-Quantum Machine Learning Approach
An ensemble machine learning model based on quantum machine learning classifiers is proposed to predict the risk of heart disease. 
The proposed model is a bagging ensemble learning model where Quantum Support Vector Classifier is used as the base classifier.
Furthermore, in order to make the model's outcomes more explainable, the importance of every single feature in the prediction is computed and visualized using SHapley Additive exPlanations (SHAP) framework.
In the experimental study, other stand-alone quantum classifiers, namely, Quantum Support Vector Classifier (QSVC), Quantum Neural Network (QNN), and Variational Quantum Classifier (VQC)
were applied and compared with classical machine learning classifiers such as Support Vector Classifier (SVC), and Artificial Neural Network (ANN). 

This project has 3 main files of code:

- Cleveland Dataset Description: represents a comprehensive analysis of the quantitative and qualitative features of the Cleveland dataset supported by figures and plots.
- 
- QSVC, SVM, QNN, ANN, VQC, and Bagging-QSVC: represents the implementation and performance of each classifier on the Cleveland dataset with different feature selection and extraction techniques.

- Model interpretation (SHAP): represents an explanation of the contribution of each feature in the Bagging-QSVC model using SHapley Additive exPlanations (SHAP) framework.
