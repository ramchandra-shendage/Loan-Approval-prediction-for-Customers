# Loan-Approval-prediction-for-Customers
Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan. The task is to check whether a customer is eligible for a loan .

This project uses Logistic Regression to predict whether a customer is likely to get a home loan based on information provided in a loan application.

The main idea is simple: understand the available customer and loan information, prepare the data, and build a classification model that can predict Loan Approved (Y) or Loan Rejected (N).

Dataset

The dataset contains 614 loan applications with information such as:

Applicant income

Co-applicant income

Loan amount

Loan amount term

Credit history

Gender, marital status, education, etc.

Loan status (target variable)

For this project, the model was built using the following numerical features:

ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, and Credit_History.

What I Did

The project follows these main steps:

Loaded and explored the dataset.

Performed basic Exploratory Data Analysis (EDA) using count plots, histograms, box plots, and a correlation heatmap.

Removed unnecessary columns and selected the numerical features for modelling.

Handled missing values using mean imputation.

Converted the target variable (Y/N) into 1/0.

Split the data into training and testing sets.

Trained a Logistic Regression model.

Evaluated the model using accuracy, confusion matrix, precision, recall, and F1-score.

Results

The Logistic Regression model achieved an accuracy of approximately 82.93% on the test dataset.

The model performed particularly well at identifying approved loans, with a recall of 98% for the approved class. However, the recall for rejected loans was only 42%, meaning that a significant number of rejected applications were incorrectly predicted as approved.

Libraries Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

SciPy

imbalanced-learn

Conclusion

This project gave me practical experience with the complete machine learning workflow, from data exploration and preprocessing to model training and evaluation. The results also show why looking beyond accuracy is important, especially when dealing with classification problems where the two classes may not be equally represented.
