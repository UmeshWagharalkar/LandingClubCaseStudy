# Lending Club Case Study
- In this case study, apart from applying the techniques of EDA, it will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
- Consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile?
- The aim of this case study is to find out the defaulters and non defaulters
- Landing Club data is used for this analysis

## Table of Contents
* [Project Objectives](#General-information)
* [Importing Libraries](#Libraries-used)
* [Loading the data](#Data-Load)
* [Inspecting The Dataframe](#Data-Read)
* [Data Cleaning](#Data-Mining)
* [Derive Columns For Analysis](#Adding-additional-columns)
* [Univariate Analysis](#Catagorical-Variables)
* [Correlation Matrix - Quantitative Variables](#Correlation)
* [Bivariate Analysis](#By-Charts)
* [Multivariate Analysis - Pair Plots](#Multivatiate)

## Conclusions
- Most of the loans taken for debt consolidation(47%) and Credit card bill payment
- Average intrest rate is 12 %
- Most of the Loan amounts are in range of 5000 - 15000
- Most of the Interest Rates on loans are in range of 10% - 15%
- Most of the borrower's Annual incomes are in range of 40000- 80000
- 14% loans were charged off out of total loan issued
- Most of the loans were taken for the purpose of debt consolidation & paying credit card bill. Number of chraged off count also high too for these loans.
- Most of the applicants are living in rented home or mortgazed their home.
- Loan amount, investor amount, funding amount are strongly correlated.
- Annual income with DTI(Debt-to-income ratio) is negatively correalted.
- Income range 80000+  has less chances of charged off.
- Income range 0-20000 has high chances of charged off
- Small Business applicants have high chnaces of getting charged off.
- Chances of charged off is increasing with grade moving from "A" towards "G"
- Charged off proportion is increasing with higher intrest rates.
- State NE has very high chances of charged off but number of applications are too low.
- States NV,CA and FL states shows good number of charged offs in good number of applications.

## Libraries Used
- numpy
- pandas
- matplotlib.pyplot
- seaborn

## Acknowledgements
- This project was inspired by upGrad
- This project was based on [https://www.lendingclub.com/](Landing-Club).


## Contact
Created by [[UmeshWagharalkar](https://github.com/UmeshWagharalkar)] - feel free to contact me!
