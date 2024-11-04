# Medical-Insurance-Cost-Prediction

Overview
This project aims to predict medical insurance costs based on demographic and lifestyle factors, using a dataset with features such as Age, BMI, and smoking status. After encoding categorical variables and scaling numeric features, we trained a Linear Regression model to estimate insurance charges..

# Project Structure
The project follows a structured approach with the following sections:

- Data Collection: Understanding the dataset and key features.
- Data Preprocessing: Cleaning and transforming data for better model performance.
- Exploratory Data Analysis (EDA): Visualizing and analyzing key patterns in the data.
- Model Selection: Training multiple machine learning models to find the best predictor.
- Model Evaluation: Assessing model performance using various metrics.
- Conclusion: Summarizing the results and providing recommendations.

# Dataset
The dataset includes multiple attributes relevant to predicting health insurance premiums. Key features are:

- age: Age of the individual.
- sex: Gender of the individual.
- bmi: Body Mass Index, an indicator of body fat based on height and weight.
- children: Number of children covered by health insurance.
- smoker: Indicates if the individual is a smoker (yes/no).
- region: Geographic location of the individual.
- charges: Target variable representing health insurance premium charges.

Here is the link to the dataset from kaggle: https://www.kaggle.com/datasets/mirichoi0218/insurance

# Getting Started
To run this project locally, follow these steps:

1. Clone the repository: git clone https://github.com/PriscyC/Medical-Insurance-Cost-Prediction/tree/main
2. Install dependencies: Ensure Python is installed, then install the required libraries
3. Run the Jupyter Notebook: Launch the notebook to view and execute the code: jupyter notebook Global_AI_Hub_Project.ipynb

# Dependencies
The primary libraries used in this project are:

- Pandas: For data manipulation and cleaning.
- NumPy: For numerical calculations.
- Matplotlib & Seaborn: For data visualization.
- Scikit-Learn: For implementing and evaluating machine learning models.

# Exploratory Data Analysis (EDA)
The EDA phase explores relationships between attributes, with visualizations showing how factors like age, BMI, and smoking status impact insurance charges. This analysis informed feature selection and preprocessing steps to improve model accuracy.

# Model Training and Evaluation
Multiple machine learning models were trained and evaluated, including:

- Linear Regressor
- Ridge Regressor
- Lasso Regressor
- Decision Tree Regressor The models were evaluated on metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). The best-performing model was chosen based on its 
  predictive accuracy and stability.

# Results
The Decision Tree Regressor achieved the best results with the following metrics:

- Accuracy Score: 0.86
- Mean Absolute Error (MAE): 2969
- Root Mean Squared Error (RMSE): 4673
- These results highlight the model's effectiveness in predicting health insurance.

# Conclusion
This project successfully demonstrates how machine learning can be used to predict medical insurance costs. Factors such as age, BMI, smoking status, and region significantly insurance prices, and this model can assist insurance providers in setting fair and personalized pricing.
