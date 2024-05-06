# Cyber_attack_prediction

# Introduction
This project explores proactive measures in cyber security to combat the increasingly sophisticated cyber attacks that threaten organizational data. Leveraging machine learning's potential, the project aims to enhance cyber defense mechanisms by effectively detecting and preventing cyber attacks before they cause harm.

# Project Objectives
1. Evaluate how machine learning algorithms can be utilized to improve cyber security measures, specifically through the detection and prevention of cyber attacks.
2. Examine the enhancement of cyber security measures through machine learning algorithms, focusing on accuracy and efficiency in detecting cyber threats.

# Data Overview
  ## Data Collection
  Data sourced from Kaggle includes detailed information on various cyber attacks categorized into nine distinct types. The data, processed     using tools like Argus and Bro-IDS, consists of comprehensive features crucial for analyzing and predicting cyber attack patterns.

  ## Data Pre-processing
  Data pre-processing involved verification, merging, and cleaning operations to prepare the dataset for effective machine learning model     training. This section details every step taken to ensure data quality and readiness for subsequent analysis.

# Methodology
The project employs Decision Trees and Random Forest models, focusing on high recall rates to minimize the risk of missing true positives in cyber attack detection. Extensive model tuning and cross-validation were conducted to optimize the model's performance.

# Models Used
- Decision Tree Classifier: Employed with hyperparameter tuning via GridSearchCV to optimize recall, ensuring that the model minimizes false negatives.
- Random Forest Classifier: Used for binary classification and also for multiclass classification with tuned hyperparameters to improve accuracy and efficiency in detecting cyber threats.
- XGBoost Classifier: Implemented for its powerful ensemble learning capabilities in handling binary classification tasks.
- Light GBM Classifier: Utilized for its efficiency in handling large datasets with many features, focusing on maximizing the recall score.

# File Descriptions
- `UNSW_NB15_training-set.csv` - Training set CSV file.
- `UNSW_NB15_testing-set.csv` - Testing set CSV file.
- `notebook.ipynb` - Jupyter notebook containing all the data analysis, model training, and evaluation code.

# Usage
To use this project:

1. Clone the repository to your local machine.
2. Unzip the dataset file in the Data folder.
3. Open the Jupyter notebook and run the cells to see the analysis and the models in action.


