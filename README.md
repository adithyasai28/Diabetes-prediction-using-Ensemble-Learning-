# Ensemble-Learning-Comparison-on-Diabetes-Classification
Comparison of ensemble learning methods on diabetes disease classification with various datasets

## About The Project

* This project compares various ensemble learning techniques for the classification of diabetes disease. Ensemble methods combine multiple machine learning models to improve predictive performance and robustness.
* In this project, we explore and compare the effectiveness of popular ensemble algorithms, such as Random Forest, AdaBoost, Gradient Boosting, and more, in diagnosing diabetes based on three different datasets of relevant features.
* Key Features:
  - Implementation of different ensemble methods for classification
  - Evaluation and comparison of model performance using metrics like accuracy, precision, recall, and F1-score
  - Jupyter notebooks with detailed explanations and visualizations
  - Dataset used for experimentation
  - Code for preprocessing, model training, and evaluation
## Technology Used
* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* xgboost
* lightgbm
* catboost
  
## Dataset Used
1. [Pima Indians Diabetes Database by UCI Machine Learning](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
2. [Frankfurt Hospital Diabetes Dataset by John](https://www.kaggle.com/johndasilva/diabetes)
3. [Sylhet Hospital Diabetes Dataset by Ishan Dutta](https://www.kaggle.com/ishandutta/early-stage-diabetes-risk-prediction-dataset)

## Workflow
- Data Preprocessing
  - MinMaxScaler for each dataset (change range of data to to fall within 0 and 1)
- Data Exploration
- Feature Engineering
- Data Splitting
  - 80% Training data
  - 20% Testing data
- Model Building
- Model Training & Testing
- Model Evaluation
  - Accuracy
  - Precision
  - Recall
  - F1-score

## Algorithms/ Methods
- Bagging
	- Bagging
	- Random Forest
	- Extra Trees
- Boosting
	- Adaptative Boosting
	- Gradient Boosting
	- Extreme Gradient Boosting
	- Light Gradient Boosting
	- Cat Boosting
- Stacking
	- Stacked Generalization
   
## Conclusion
* In general, all Boosting methods give the best results for all datasets, but specifically, the Light Gradient Boosting method gives the best results in most of the data (Dataset 2 & Dataset 3)
