This project analyzes factors like Gender, Ethnicity, Parental Education Level, Lunch, and Test Preparation Course to understand their impact on students' test scores. The goal is to identify influential factors affecting student performance, potentially guiding educational improvements.

Overview
Exploratory Data Analysis (EDA): Analyze data to uncover patterns.
Correlation Analysis: Visualize relationships between features.
Predictive Modeling: Train regression models to predict scores.
Evaluation: Use metrics like MAE, RMSE, and R² to assess model performance.
Dataset
The dataset includes:

Gender, Ethnicity, Parental Education, Lunch, Test Prep Course
Test Scores: Target variable (outcome)
Project Structure
graphql
Copy code
├── StudentPerformance.csv       # Dataset file
├── predictor.ipynb              # EDA and modeling notebooks                  
├── README.md                    # Project README file                     
Dependencies
Install dependencies using pip install -r requirements.txt.

pandas, numpy, matplotlib, seaborn, scikit-learn
Analysis and Modeling
EDA: Examine data distribution and feature relationships.
Correlation Matrix: Visualize correlations using Seaborn.
Models Used: Linear Regression, Lasso, Ridge, KNN, Decision Tree, Random Forest.
Evaluation: Calculate MAE, RMSE, and R² for each model.
Usage
Clone the repo:
bash
Copy code
git clone https://github.com/yourusername/student-performance-analysis.git
Install dependencies:
bash
Copy code
Key Insights
Significant Factors: Parental education and test prep course impact scores.
Best Models: Random Forest and Decision Tree performed well.
Contributors
Satyendra Shukla
