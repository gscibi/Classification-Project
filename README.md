# Classification-Project

### Overview

The goal of this Project is to build a model to predict if a customer has good or bad credit (class column).
Source of the data: https://www.kaggle.com/code/raphaelmarconato/credit-risk-eda-and-machine-learning-73/input

### Approach

The approach for this problem is the following:
    1. Data import --> explore.ipynb
    2. Exploratory Data Analysis --> explore.ipynb
    3. Feature Engineering -->
    4. Classification Model -->
    5. Iteration -->

### Notes on The project
checking_status: object, has 4 values, 
    <0
    0<=X<200
    no checking
    >=200

duration: float 

credit_history: object, has 5 values,
    critical/other existing credit
    existing paid
    delayed previously
    no credits/all paid
    all paid

purpose: object, has 10 values, and indicates the purpose of the credit

credit_amount: float - amount of the credit

savings_status: object, has 5 values,
    no known savings
    <100
    500<=X<1000
    >=1000
    100<=X<500

employment: object, has 5 values,
    >=7
    1<=X<4
    4<=X<7
    unemployed
    <1

installment commitment: float (could be int), values from 1 to 4

personal_status: object, has 4 values:
    male single
    female div/dep/mar
    male div/sep
    male mar/wid

other_parties: object, has 3 values, 
    none
    guarantor
    co applicant

residence_since: float (could be int), values from 1 to 4

property_magnitude: object, has 4 values:
    real estate
    life insurance
    no known property
    car

age: float

other_payment_plans: object, has 3 values
    none
    bank
    stores

housing: object, has 3 values
    own
    for free
    rent

existing credits: float (could be int), values from 1 to 4

job: object, has 4 values:
    skilled
    unskilled resident
    high qualif/self emp/mgmt
    unemp/unskilled non res

num_dependents: float

own_telephone: object, has 2 values
    yes
    none

foreign_worker: object, has 2 values
    yes
    no

class: object, has 2 values
    good
    bad

# Encoding Explained
Checkign Status - it can be sequentially classified
Credit History - unclear how it would be classified sequentially
Purpose - One hot encoding
Savings Status - it can be sequentially classified
Employment - it can be sequentially classified
Personal Status - One hot encoding
Other parties - One hot encoding
Property Magnitude - One hot encoding
Other Payment Plans - One hot encoding
Housing - Unclear
Job - Unclear
Own telefone - One hot encoding
foreign worked - One hot encoding






