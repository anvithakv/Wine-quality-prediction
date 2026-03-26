# Wine-quality-prediction
ML-based wine quality prediction system using chemical attributes and classification models.

## - Project Overview
- This project builds a machine learning model to predict the quality of wine based on its chemical properties
- The system classifies wine quality using input features

## - Dataset
- File Name - winequality-red.csv
- The dataset contains the following features
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target)

## - Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

## - Data Preprocessing
- Checked for missing values
- Separated features and target variable
- Converted quality into classification labels if required
- No categorical encoding required as data is numerical

## - Model Building
- Algorithm used
- Logistic Regression or Random Forest Classifier
- Data split
- 80 percent training data
- 20 percent testing data
- Feature scaling using StandardScaler

## - Model Evaluation
- Accuracy score is used to evaluate performance
- Confusion matrix can be used for better understanding
- Predictions are compared with actual values

## - Prediction System
- A prediction function is created
- Input data is converted into array
- Data is scaled using trained scaler
- Prediction is made using trained model

## - Input Format
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

## - Output
- Predicted Wine Quality (e.g., Good or Bad or quality score)

## - How to Run
- Install required libraries
- pip install pandas numpy scikit-learn
- Run the Python file or Jupyter Notebook
- Provide input to prediction function

## - Future Improvements
- Use advanced models like XGBoost
- Perform hyperparameter tuning
- Add visualization for feature importance
- Build web app using Streamlit


