# Customer Churn Prediction

This project predicts whether a customer is likely to churn (leave the bank) based on various features like age, geography, balance, and activity. The model is built using a machine learning classifier and is deployed as a web application using Streamlit.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Project Structure](#project-structure)
5. [How to Run](#how-to-run)
6. [Deployment](#deployment)
7. [Technologies Used](#technologies-used)
8. [Model Details](#model-details)
9. [Acknowledgments](#acknowledgments)

## Project Overview
The goal of this project is to build a machine learning model to predict customer churn for a bank. Customer churn prediction helps the bank to identify at-risk customers and take measures to retain them.

## Dataset

The dataset contains several features related to customer demographics, account information, and activity. Key columns include:

- **RowNumber**: A unique identifier for each row
- **CustomerId**: Unique ID for the customer
- **Surname**: The surname of the customer
- **CreditScore**: Credit score of the customer
- **Geography**: The location (country) of the customer
- **Gender**: Gender of the customer (Male or Female)
- **Age**: Age of the customer
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: The account balance of the customer
- **NumOfProducts**: Number of products the customer is using
- **HasCrCard**: Whether the customer holds a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated annual salary of the customer
- **Exited**: The target variable (1 = Exited, 0 = Stayed), indicating whether the customer churned or not

## Installation

### Requirements
- Python 3.7+
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Pickle

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shyam1719/Customer_churn_prediction.git
2. **Navigate to the project directory**:
   ```bash
   cd Customer_churn_prediction
3. **Set up a virtual environment **:
   ```bash
   python -m venv myenv
    source myenv/bin/activate  # On Windows use: myenv\Scripts\activate
4. **Install the required dependencies**:
   ```bash
    pip install -r requirements.txt
