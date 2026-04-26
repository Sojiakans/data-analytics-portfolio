# data-analytics-portfolio
Portfolio showcasing data analytics projects using SQL, Python, and Power BI

Overview: Project focuses on detecting anomaluos patterns in data using machine learning techniques. Thw goal is to identify rare and unusal observations that may indicate fraud, system failures or abnormal behavior
Problem Statement: Anomalies are rare but critical and indicates Fraudulent Transaction. This project builds a robust pipeline to automatically detect such anomalies in a dataset
Dataset: link:          type: (tables)        Size: (    rows , 30 features)    Numercal features:( )    Categorical features: ()

Approach: 
  1. Data Preprocessing
       a. Handling Missing Values
       b. Feature scaling (StandardScaler / MinMaxScaler)
       c. Encoding categorical varables
  2. Exploratory Data Analysis (EDA)
       a. Distribution analysis
       b. Correlation heatmaps
       c. Outlier visualization
3. Models Used
       a. Isolation Forest
       b. SVM
       c. Autoencoder (Neural Network)
4. Evaluation Strategy
   Note: Accuracy is misleading—because a model can get very high accuracy by simply predicting the majority class (non-fraud) all the time. Thus evaluation startegy that focus on how well the model identifies the rare class. The formula does not distinguish between classes
        techniques: Precision, Recall, F1-score, ROC-AUC
5. Results

Model            Precison            Recall         F1 Score

Random Forest
SVM
Autoencoder 

6. Visualizations
       a. Anomaly score distribution
       b. PCA / t-SNE plots
       c. Reconstruction error plots


How Model was implemented
       a. Run training
          python src/train.py
       b. Evaluate model
          python src/evaluate.py

7. Project Structure
│── data
│── notebooks
│── src
│── models
│── reports
│── app

8. Key Learnings
        a. Handling highly imbalanced datasets
        b. Trade-offs between unsupervised and supervised methods
        c. Importance of feature engineering in anomaly detection

9. Challenges in evaluating unlabeled anomalies
        Future Improvements
        Deploy as a real-time API
        Add streaming anomaly detection
        Improve explainability (SHAP, LIME)
        Hyperparameter tuning
   
10. Tech Stack
        Python
        Scikit-learn
        TensorFlow / PyTorch
        Pandas, NumPy
        Matplotlib, Seaborn

        

     


