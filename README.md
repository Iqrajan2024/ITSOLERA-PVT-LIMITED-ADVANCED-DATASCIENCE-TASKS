# Task 1: End-to-End ML System with Streamlit GUI

## Problem Statement
Customer churn is a critical issue for businesses, as losing customers directly impacts revenue. The goal of this task is to build a complete machine learning pipeline to predict customer churn and deploy it using an interactive Streamlit GUI.

## Task Objective
- Build an end-to-end ML pipeline  
- Train and compare multiple models  
- Deploy the best model using Streamlit  
- Provide real-time predictions with probability  

## My Approach
- Loaded and preprocessed the dataset  
- Encoded categorical variables using Label Encoding  
- Split data into training and testing sets  
- Trained multiple models:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
- Evaluated models and selected the best one  
- Saved the model using joblib  
- Developed a Streamlit GUI with:
  - User input fields  
  - Prediction output with probability  
  - Dataset preview  
  - Feature importance visualization  

## Results and Findings
- Tree-based models performed better than linear models  
- The selected model achieved strong predictive performance  
- GUI enabled easy interaction for non-technical users  
- Feature importance revealed key drivers of churn  

## 🧾 Conclusion
This task demonstrated the full ML lifecycle, from preprocessing to deployment. The Streamlit interface made the model accessible and practical for real-world use.


#  Task 2: Recommendation System with Streamlit GUI

## Problem Statement
With the increasing volume of digital content, users need help discovering relevant items. This task focuses on building a movie recommendation system using content-based filtering.

## Task Objective
- Build a recommendation system using cosine similarity  
- Implement content-based filtering  
- Develop an interactive Streamlit GUI  

## My Approach
- Used MovieLens dataset with movie titles and genres  
- Cleaned and preprocessed text data  
- Converted genres into numerical form using TF-IDF  
- Computed cosine similarity between movies  
- Built a recommendation function:
  - Input: movie title  
  - Output: top 5 similar movies with similarity scores  
- Developed Streamlit GUI:
  - Text input for movie name  
  - Display of recommendations  
  - Dataset preview  

##  Results and Findings
- The system successfully recommended similar movies  
- Movies with similar genres had higher similarity scores  
- TF-IDF and cosine similarity worked effectively  
- GUI improved usability and user experience  

##  Conclusion
The recommendation system effectively personalized user experience using similarity-based techniques and provided an intuitive interface via Streamlit.


# Task 3: Model Optimization and Evaluation

## Problem Statement
Choosing the right model is essential for reliable predictions. This task focuses on optimizing and evaluating multiple models using hyperparameter tuning and performance metrics.

##  Task Objective
- Train multiple models  
- Perform hyperparameter tuning  
- Evaluate models using multiple metrics  
- Select the best model  

## My Approach
- Trained three models:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
- Applied hyperparameter tuning using:
  - GridSearchCV / RandomizedSearchCV  
- Evaluated models using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  
  - ROC-AUC  
- Compared models using tables and visualizations  
- Selected best model based on performance metrics  

## Results and Findings
- XGBoost achieved the best overall performance  
- Hyperparameter tuning improved model accuracy  
- F1-score provided better insight for imbalanced data  
- Visualization helped compare models effectively  

## Conclusion
This task highlighted the importance of systematic evaluation and tuning. Selecting models based on multiple metrics ensures better real-world performance.

---

# Task 4: Feature Engineering Challenge

##  Problem Statement
Raw features often do not capture complex patterns in data. This task focuses on improving model performance through feature engineering and selection techniques.

##  Task Objective
- Create new features  
- Select important features  
- Improve model performance  
- Compare results before and after feature engineering  

## My Approach
- Created new features:
  - Polynomial features  
  - Interaction features  
  - Binning (categorization)  
- Applied feature selection techniques:
  - Correlation analysis  
  - Feature importance (Random Forest)  
  - Recursive Feature Elimination (RFE)  
- Trained model using engineered features  
- Compared performance with baseline model  

##  Results and Findings
- Feature engineering improved model performance  
- Interaction and polynomial features captured complex relationships  
- Feature selection reduced noise and redundancy  
- Improved F1-score and overall model robustness  

##  Conclusion
Feature engineering significantly enhanced predictive performance. Proper feature selection improved efficiency and generalization of the model.
