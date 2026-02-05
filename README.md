# House Price Prediction - Advanced Regression

This repository contains a comprehensive machine learning project aimed at predicting house sale prices using various regression techniques. The project utilizes the Kaggle "House Prices - Advanced Regression Techniques" dataset to build a model with high out-of-sample accuracy.

## 🎯 Project Aim
The goal is to analyze house features (79 explanatory variables) and predict the final **SalePrice** of residential homes. The project follows a complete data science workflow, from data cleaning and exploratory analysis to model training and final submission generation.

## 🛠️ Tech Stack
- **Language:** Python
- **Data Manipulation:** `Pandas`, `NumPy`
- **Visualization:** `Matplotlib`, `Seaborn`
- **Machine Learning:** `Scikit-learn` (Decision Tree, SVM, LabelEncoder)

## 📊 Workflow
1. **Exploratory Data Analysis (EDA):** Identified significant numerical features by calculating correlation coefficients with the target variable (`SalePrice`).
2. **Data Pre-processing:**
   - **Handling Missing Values:** Dropped columns where more than 50% of the data was missing (e.g., `PoolQC`, `MiscFeature`, `Alley`, `Fence`, and `MasVnrType`).
   - **Feature Selection:** Focused on highly correlated features to optimize model performance.
   - **Encoding:** Applied `LabelEncoder` to transform categorical variables into a machine-readable format.
3. **Modeling:** Implemented and compared:
   - **Decision Tree Regressor**
   - **Support Vector Machine (SVM)**

## 📁 Project Structure
- `house-price-data-beginner-s-guide.ipynb`: The main Jupyter Notebook containing the full analysis and code.
- `test_presd_submission.csv`: The final predicted house prices for the test dataset.

## 🚀 Usage
1. Clone the repository.
2. Ensure you have the required datasets (`train.csv` and `test.csv`) in the input directory.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
