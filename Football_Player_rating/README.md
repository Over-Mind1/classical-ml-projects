# FIFA Overall Player Ratings Prediction Using Regression Methods

## Project Overview
This project aims to predict FIFA player overall ratings using various regression techniques. The dataset contains key player attributes such as passing, shooting, dribbling, and physicality. By leveraging classical machine learning models, we analyze feature importance and optimize predictive performance.

## Table of Contents
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [How to Run the Notebook](#how-to-run-the-notebook)
- [Requirements](#requirements)
- [Conclusion](#conclusion)

## Dataset
- The dataset includes FIFA player attributes, such as:
  - **Age, Height, Weight**
  - **Position, Club, Nationality**
  - **Skill Attributes (Passing, Dribbling, Shooting, etc.)**
  - **Overall Rating (Target Variable)**
- Data preprocessing includes handling missing values, feature scaling, and encoding categorical variables.

## Methodology
1. **Data Preprocessing**: Cleaning, encoding categorical features, and feature selection.
2. **Exploratory Data Analysis (EDA)**: Visualizing distributions, correlations, and feature importance.
3. **Model Training**: Applying multiple regression techniques.
4. **Hyperparameter Tuning**: Optimizing models for better performance.
5. **Model Evaluation**: Comparing models based on error metrics.

## Models Used
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

## Evaluation Metrics
The models are evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score (Coefficient of Determination)**

## Results
- Feature importance analysis reveals that **dribbling, passing, and shooting** are the most influential attributes.
- Ensemble models like **Random Forest and Gradient Boosting** outperform linear models in predictive accuracy.
- The final model achieves a strong balance between interpretability and accuracy.

## How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/classical-ml-projects.git
   cd classical-ml-projects/proj1
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook player_rating.ipynb
   ```
4. Run all cells to train models and evaluate results.

## Requirements
Ensure you have the following Python libraries installed:
```bash
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
```

## Conclusion
This project demonstrates how regression techniques can be applied to predict FIFA player ratings. Feature selection and model tuning significantly improve performance, making ensemble methods the best fit for this task.

📌 *Future improvements may include deep learning approaches for enhanced accuracy!*


