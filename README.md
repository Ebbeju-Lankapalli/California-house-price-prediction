# 🏡 California Housing Price Prediction

An end-to-end Machine Learning project that predicts California housing prices using regression algorithms. This project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, evaluation, and prediction on unseen data.

---

## 📌 Project Overview

California housing prices are influenced by several factors such as geographical location, median income, population density, and housing characteristics.

The objective of this project is to build regression models that accurately predict the **median house value** of different regions in California.

This project follows a complete data science workflow and compares multiple machine learning algorithms to identify the best-performing model.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing
- Handle missing values
- Perform Exploratory Data Analysis (EDA)
- Engineer meaningful features
- Train multiple regression models
- Tune model hyperparameters using GridSearchCV
- Evaluate and compare model performance
- Predict house prices for unseen data
- Generate a submission-ready CSV file

---

# 📂 Dataset

The dataset contains housing information collected from different districts in California.

### Features

| Feature | Description |
|----------|-------------|
| longitude | Longitude of the district |
| latitude | Latitude of the district |
| housing_median_age | Median age of houses |
| total_rooms | Total number of rooms |
| total_bedrooms | Total number of bedrooms |
| population | Population of the district |
| households | Number of households |
| median_income | Median income |
| ocean_proximity | Distance from the ocean |

### Target

- **median_house_value**

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Missing value analysis
- Duplicate value detection
- Statistical summary
- Univariate Analysis
- Bivariate Analysis
- Correlation Heatmap
- Distribution plots
- Boxplots
- Scatter plots
- Ocean proximity analysis
- Feature correlation analysis

---

# ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Median Imputation for missing values
- Standard Scaling of numerical features
- One-Hot Encoding of categorical variables
- ColumnTransformer Pipeline
- Train-Test Split

---

# 🚀 Feature Engineering

Three additional features were created to improve model performance.

- Rooms per Household
- Bedrooms per Room
- Population per Household

---

# 🤖 Machine Learning Models

The following regression models were implemented and compared.

- K-Nearest Neighbors Regressor (KNN)
- Support Vector Regressor (SVR)
- Decision Tree Regressor

---

# 🔧 Hyperparameter Tuning

GridSearchCV was used to optimize model parameters.

### KNN

- Number of Neighbors
- Distance Metric
- Weight Function

### SVR

- C
- Gamma
- Epsilon

### Decision Tree

- Maximum Depth
- Minimum Samples Split
- Minimum Samples Leaf

---

# 📈 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Cross Validation
- Predicted vs Actual Plot
- Residual Plot
- Feature Importance

---

# 🏆 Model Comparison

| Model | R² Score |
|--------|---------:|
| KNN | **0.7534** |
| Decision Tree | 0.7244 |
| SVR | 0.2800 |

**Best Model:** K-Nearest Neighbors (KNN)

---

# 📊 Feature Importance

The most influential features identified by the Decision Tree model were:

- Median Income
- Ocean Proximity (INLAND)
- Population per Household
- Longitude
- Latitude

---

# 📸 Sample Visualizations

The project includes several visualizations including:

- Target Distribution
- Correlation Heatmap
- Scatter Plots
- Boxplots
- Feature Importance
- Predicted vs Actual
- Residual Plots
- Model Comparison

---

# 💡 Key Learnings

Through this project, I learned:

- End-to-end machine learning workflow
- Data preprocessing techniques
- Feature engineering
- Regression model implementation
- Hyperparameter tuning using GridSearchCV
- Model comparison and evaluation
- Feature importance interpretation
- Building reusable preprocessing pipelines

---

# 🔮 Future Improvements

Potential improvements include:

- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost
- LightGBM
- CatBoost
- Ensemble Learning
- Model Deployment using Streamlit or Flask
- Docker Containerization
- CI/CD Integration

---
