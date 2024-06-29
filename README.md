# Parkinson-s-Disease-Prediction-using-Machine-Learning
This project develops a machine learning model to predict Parkinson's disease based on vocal measurements. It includes data loading, preprocessing (shuffling, splitting, standardizing, handling imbalance), training with ensemble methods, and evaluation using key metrics to ensure accuracy and reliability.
Libraries Used:
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Seaborn: For data visualization.
Matplotlib: For plotting graphs.
Joblib: For saving and loading machine learning models and preprocessing tools.
Scikit-learn: For model training, data preprocessing, and evaluation.
Imbalanced-learn (imblearn): For handling imbalanced datasets, specifically using SMOTE (Synthetic Minority Over-sampling Technique).
Outputs of the Project:
Preprocessed Data: The dataset is preprocessed by shuffling, splitting, standardizing, and balancing.
Trained Model: A machine learning model trained to predict the presence of Parkinson's disease.
Scaler Object: The StandardScaler object used for standardizing the dataset, saved using Joblib for future use.
Model Performance Metrics: Evaluation metrics such as accuracy, precision, recall, and F1-score, which provide insights into the model's effectiveness.
Plots and Visualizations: Various plots generated using Seaborn and Matplotlib to visualize data distributions, feature importance, and model performance.
