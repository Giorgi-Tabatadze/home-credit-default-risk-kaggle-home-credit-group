# Home Credit Default Risk Kaggle Competition

## Introduction
This project is part of the Home Credit Default Risk competition hosted on Kaggle. It aims to predict loan repayment probabilities for individuals with little to no credit history. The challenge is a standard supervised classification task, focusing on determining if an applicant will repay a loan based on historical loan application data.

Competition link: https://www.kaggle.com/competitions/home-credit-default-risk

## Objective
The primary goal is to use machine learning to predict the likelihood of an applicant repaying a loan. This involves classifying applicants into two categories:
* 0: Will repay loan on time.
* 1: Will have difficulty repaying loan.

## Data Overview
The dataset, provided by Home Credit, encompasses various aspects of the loan application process and applicant's credit history, divided into several files:

1. **Application Data (`application_train/application_test`):**
   * Main dataset for training and testing. Each loan application is a row, identified by `SK_ID_CURR`.

2. **Bureau Data (`bureau`):**
   - Details on client's previous credits from other financial institutions.

3. **Bureau Balance (`bureau_balance`):**
   * Monthly data about the previous credits in the bureau.

4. **Previous Applications (`previous_application`):**
   * Data on previous loan applications at Home Credit.

5. **POS Cash Balance (`POS_CASH_BALANCE`):**
   * Monthly details of previous POS or cash loans at Home Credit.

6. **Credit Card Balance (`credit_card_balance`):**
   * Monthly records of previous credit card balances with Home Credit.

7. **Installments Payments (`installments_payments`):**
   * Payment history for previous loans at Home Credit.


## Note
For comprehensive understanding and further details, the columns are described in `HomeCredit_columns_description.csv`. I am not uploading datasets here as they are large for github so you can view full dataset as well as description on the competition website above. 

## Jump to notebooks

 - [EDA and Base Control Model](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/starting-model.ipynb)
 - [Feature Tools Feature Name Generation](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/generate_feature_names.ipynb)
 - [Handling Time Feature Name Generation](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/time_feature_names.ipynb)
  - [Partitioning Data For Dask](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/partition_feature_matrix.ipynb)
 - [Partitioningg Time Data For Dask](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/time_features_partition.ipynb)
  - [Compute Feature Matrix With Feature Tools and Dask](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/compute_feature_matrix.ipynb)
 - [Compute Time Feature Matrix With Dask And FT](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/time_features_compute.ipynb)
- [Feature Selection](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/feature_selection.ipynb)
 - [Baesian Search](https://github.com/Giorgi-Tabatadze/home-credit-default-risk-kaggle-home-credit-group/blob/main/baesian_search.ipynb)


