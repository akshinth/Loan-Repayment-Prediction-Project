# Loan Repayment Prediction Project

## Overview

This project explores publicly available data from **LendingClub.com** to predict whether or not a borrower will repay their loan in full. Lending Club connects borrowers with investors, and the goal is to create a model that predicts loan repayment based on borrower profiles.

## Project Structure

1. **Data Loading and Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preparation**
4. **Model Training**
5. **Model Evaluation**
6. **Conclusion**

## Data Description

The dataset contains the following columns:

- **credit.policy**: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
- **purpose**: The purpose of the loan (e.g., "credit_card", "debt_consolidation").
- **int.rate**: The interest rate of the loan as a proportion.
- **installment**: The monthly installments owed by the borrower if the loan is funded.
- **log.annual.inc**: The natural log of the self-reported annual income of the borrower.
- **dti**: The debt-to-income ratio of the borrower.
- **fico**: The FICO credit score of the borrower.
- **days.with.cr.line**: The number of days the borrower has had a credit line.
- **revol.bal**: The borrower's revolving balance.
- **revol.util**: The borrower's revolving line utilization rate.
- **inq.last.6mths**: The borrower's number of inquiries by creditors in the last 6 months.
- **delinq.2yrs**: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
- **pub.rec**: The borrower's number of derogatory public records.
- **not.fully.paid**: 1 if the borrower did not fully pay back the loan, 0 otherwise.

## Exploratory Data Analysis

- Visualized the distribution of **FICO scores** based on credit policy and loan repayment status.
- Examined the count of loans by **purpose**, colored by repayment status.
- Investigated the relationship between **FICO scores** and **interest rates**.

## Data Preparation

- Converted the **purpose** column to **dummy variables**.
- Split the data into **training and testing sets**.

## Model Training

### Decision Tree

- Trained a **Decision Tree Classifier**.
- Evaluated the model's performance using **classification report** and **confusion matrix**.

### Random Forest

- Trained a **Random Forest Classifier**.
- Evaluated the model's performance and compared it to the Decision Tree.

## Results

- The **Random Forest** model performed better than the **Decision Tree** model.
- The model's performance metrics were evaluated using **precision, recall, f1-score**, and **confusion matrix**.

## Conclusion

- Summarized findings and discussed model performance.
- Mentioned potential improvements and next steps.

## Usage

To run this project, you need to have Python installed along with the following libraries:

- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **scikit-learn**

