🏥 Medical Charges Prediction from Health Features

Welcome to my Medical Charges Prediction project!
This project dives into the relationship between health-related features and insurance costs, applying machine learning techniques to predict future medical charges — helping healthcare providers and individuals anticipate expenses better.

🚀 Project Overview

Healthcare costs are influenced by personal, demographic, and lifestyle factors.
Using machine learning models, this project aims to predict an individual's medical charges based on their:

Age
Gender
Body Mass Index (BMI)
Smoking habits
Region of residence
Number of children

📂 Dataset Information

Source: Health Insurance Data
Features:
age: Age of primary beneficiary
sex: Gender of the patient
bmi: Body mass index
children: Number of children/dependents covered by insurance 
smoker: Smoking status (yes/no)
region: Residential region in the US
charges: Individual medical costs billed by health insurance

🛠️ Project Workflow

1. Data Understanding
Loaded the dataset and explored its structure and missing values.
Verified data types and cleaned unnecessary inconsistencies.

2. Exploratory Data Analysis (EDA)
Visualized the distribution of numerical and categorical features.
Identified the strong relationship between smoking and charges.
Noted that charges increase with age and BMI.

3. Data Preprocessing
Categorical variables like sex, smoker, and region were encoded into numeric form.
Performed train-test split for better model evaluation.

4. Model Building
Applied Linear Regression to understand baseline relationships.
Trained the model using:

Input Features: age, sex, bmi, children, smoker, region
Target Variable: charges

5. Model Evaluation
Evaluated model performance using:
R² Score (Goodness of fit)
Root Mean Squared Error (RMSE)
Observed that the model performed well in capturing the underlying trend.

📊 Key Visualizations

Scatter Plots of charges vs. BMI and age.
Bar Charts showing smoker vs. non-smoker average charges.
Heatmap showcasing feature correlations.

💡 Major Insights
Smokers are charged significantly more for medical insurance compared to non-smokers.
Older individuals and those with higher BMI also tend to have higher charges.
The region has a small but visible effect on medical charges.

📈 Model Performance

Metric	Value
R² Score	Good (Captured a strong trend between features and charges)
RMSE	Low enough (indicating reliable predictions)

🌟 Future Enhancements
Test advanced models like Gradient Boosting Regressor or XGBoost to possibly improve performance.
Hyperparameter tuning for optimal model settings.
Deploy the prediction system as an interactive web application using Streamlit or Flask.

📣 Conclusion
This project highlights the real-world impact of demographic and lifestyle factors on healthcare costs and showcases how machine learning can provide predictive insights that empower better financial and medical decision-making.

