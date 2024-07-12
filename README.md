Larissa Fierle, Maria Villacreces, Tomas Echeverria, Milena Cuao
# PROJECT_4 FINANCE LOAN APPROVAL PREDICTION DATA 
![image](https://github.com/user-attachments/assets/45dda312-7783-44a7-b97f-26e74d2e67cd)
## OVERVIEW
This project aims to predict the approval of finance loan applications using various machine learning models. We explore a dataset, apply different models, and evaluate their performance to determine the best approach for accurate predictions.
## PURPOSE
The purpose of this project is to provide a comprehensive analysis and implementation of machine learning techniques for predicting loan approvals. By understanding the factors that influence loan approval, we can assist financial institutions in making more informed decisions, potentially reducing default rates and improving customer satisfaction.
## PROJECT STRUCTURE
• Imported essential libraries: matplotlib, pandas, numpy, scipy, hvplot.pandas, and sklearn.metrics.

• Loaded the finance loan dataset from a CSV file into a Pandas DataFrame.

• Obtained a summary of the DataFrame using info() to understand data types and null values.

• Combined ApplicantIncome and CoapplicantIncome into a new column, Total_Income.

• Created income categories by binning ApplicantIncome into 'Very_Low', 'Low', 'Average', 'High', and 'Very_High'. • Converted Income_Category to string type for easier manipulation.

• Renamed columns for better clarity.

• Checked for and identified missing values using isna().any().

• Removed duplicate rows using the duplicated() method.

• Dropped rows with missing values using dropna().

• Defined feature set X and target variable y for machine learning models.

• Split the data into training and testing sets.

• Trained the Logistic Regression model on the training data.

• Made predictions using the Logistic Regression model on the testing data.

• Evaluated the Logistic Regression model using a confusion matrix and classification report.

• Standardized features using StandardScaler.

• Trained the Decision Tree model on the scaled training data.

• Made predictions using the Decision Tree model on the scaled testing data.

• Evaluated the Decision Tree model using a confusion matrix and classification report.

• Compared the performance of Logistic Regression and Decision Tree models using evaluation metrics.

• Visualization: tableau.

## RESULTS
## Decison Tree
<img width="410" alt="image" src="https://github.com/user-attachments/assets/2b1625d8-3238-44c3-95b2-fe66586d8347">

## Logistic Regresion with dummies
<img width="381" alt="image" src="https://github.com/user-attachments/assets/fd4e014f-b86b-4863-9cdb-2ccd2d942b4c">

## Tableau dashboard

<img width="475" alt="image" src="https://github.com/user-attachments/assets/97e920be-a4a9-4ceb-b253-c7b2fd66fab2">

tableau link: https://public.tableau.com/app/profile/larissa.fierle/viz/finance_loan/Dashboard1


