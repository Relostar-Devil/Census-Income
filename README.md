# Census Income

A comprehensive machine learning project for predicting whether an individual earns over \$50K per year based on the US Census Income dataset from the UCI Machine Learning Repository. This notebook-driven project guides you through data preprocessing, exploratory data analysis (EDA), and predictive modeling using several state-of-the-art algorithms.

## Project Overview

- **Objective:**  
  Predict the income level of individuals (<=50K or >50K) by analyzing demographic features from census data.

- **Dataset:**  
  The dataset contains detailed information on over 48,000 individuals collected during the 1994 US census. For more details about the dataset, please refer to its description on the UCI Machine Learning Repository.
 https://archive.ics.uci.edu/ml/datasets/census+income

- **Approach:**  
  The project involves:
  - Data ingestion and cleaning
  - Exploratory Data Analysis (EDA) with visualizations
  - Feature engineering and scaling using tools like `LabelEncoder` and `StandardScaler`
  - Training and evaluating multiple classification models, including:
    - Logistic Regression
    - Support Vector Classifier (SVC)
    - Random Forest Classifier
    - Gradient Boosting Classifier

## Technical Highlights

- **Data Handling:**  
  - Uses `pandas` and `numpy` for efficient data manipulation.
  - Reads multiple CSV data sources seamlessly.

- **Visualization & EDA:**  
  - Employs `matplotlib` and `seaborn` to create insightful visualizations.
  - Generates data summaries and statistical insights.

- **Machine Learning Pipeline:**  
  - Splits the dataset into training and testing sets using `train_test_split`.
  - Implements several machine learning algorithms from the `scikit-learn` package.
  - Evaluates model performance with `accuracy_score` and `classification_report`.
 
## Project Structure

- `Census-Income.ipynb` – Main Jupyter Notebook containing the full workflow from data ingestion to model evaluation.
- Data files – CSV files containing the census data.
- Additional documentation and visualizations are embedded within the notebook.
