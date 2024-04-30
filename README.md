
# Credit Analisys & Fraud Detection (Análise de Crédito e Detecção de Fraudes)

## Introduction (Introdução)
This project focuses on Data Analysis and Forecast using the CRISP-DM approach, sorting customers and checking fraud possibilties. Both datasets used in this project are sourced from Kaggle.


## Dataset - 1
 Mobile Money Transactions
- The dataset is a synthetic dataset generated using the PaySim simulator.
- PaySim simulates mobile money transactions based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country.
- The dataset is scaled down to 1/4 of the original dataset and is created specifically for Kaggle.
- Link to the dataset: [PaySim Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)


## Features (Atributos)

- `step`: One unit of time in the real world. In this case, 1 == 1 hour of time, totaling 744 steps (30 days of simulation).
- `type`: Type of transaction (CASH-IN, CASH-OUT, DEBIT, PAYMENT, and TRANSFER).
- `amount`: Amount of money transacted in the local currency.
- `nameOrig`: Originator of the transaction.
- `oldbalanceOrg`: Initial balance of the sender's account.
- `newbalanceOrig`: Balance after the transaction of the sender.
- `nameDest`: Destination of the transaction.
- `oldbalanceDest`: Initial balance of the destination account. There is no information about customers starting with "M" (Merchants).
- `newbalanceDest`: Balance after the transaction of the destination account. There is no information about customers starting with "M" (Merchants).
- `isFraud`: Transactions identified as fraudulent.
- `isFlaggedFraud`: Business model that controls massive transfers and marks them as illegal transfers.
- 
## Libraries Used (Bibliotecas Utilizadas)

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn

## Usage (Utilização)
The project includes data exploration, visualization, preprocessing, model training, and evaluation using various classification algorithms.

## Dataset - 2
Credit Risk Dataset

- This dataset consists of credit history records of customers from a financial institution.
- The aim is to predict possible credit defaulters and assist financial institutions in taking appropriate steps.
- Link to the Dataset: [Credit Risk](https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset)


## Features (Atributos)

- `loan_amnt`: Loan amount
- `term`: Term
- `int_rate`: Interest rate
- `installment`: Installment
- `grade`: Credit rating grade
- `emp_length`: Employment length
- `home_ownership`: Home ownership status
- `annual_inc`: Annual income
- `verification_status`: Verification status
- `purpose`: Purpose of loan


## Libraries Used (Bibliotecas Utilizadas)

- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Usage (Utilização)

The project involves data preprocessing, visualization, and classification model training to predict credit defaulters.

## Installation (Instalação)
To run the project, you need to install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn plotly
```
Than run the code in your prefered IDE.
