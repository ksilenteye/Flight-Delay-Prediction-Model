Flight Delay Prediction Model✈️
This repository contains the code and documentation for a machine learning project designed to predict flight arrival delays.
      Project Overview
The primary goal is to classify whether a flight will be delayed (arriving $> 15$ minutes late) or on-time/early based on pre-flight and in-flight features. 
The project focuses on building a robust, production-ready pipeline that rigorously prevents data leakage.

      Key Technologies and ModelsLanguage: 
PythonLibraries: pandas, scikit-learn, joblibArchitecture: End-to-End Scikit-learn Pipeline with ColumnTransformer for consistent data preprocessing.Models:Logistic Regression (Baseline)Random Forest Classifier (Selected Model): Achieved $\mathbf{91.47\%}$ Accuracy and $\mathbf{94\%}$ Precision for the delayed class, making it highly reliable for deployment.
Handling Imbalance:
Used class_weight='balanced' to mitigate the minority class issue (delayed flights).Repository ContentsFDP_classification_Model.ipynb: The main Jupyter Notebook containing the full development and evaluation workflow.requirements.txt: Lists all necessary Python dependencies (e.g., scikit-learn, seaborn).flight_delay_random_forest_pipeline.joblib: The serialized, production-ready Random Forest model pipeline
