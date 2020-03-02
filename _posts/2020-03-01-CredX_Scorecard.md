---
title: "Case Study: CredX Scorecard"
date: 2020-03-02
excerpt: Data Science
categories:
  - Machine Learning
tags:
  - Machine Learning
  - Data Science
header:
 image: "/images/unsplash-image-2.jpg"
---

## Business understanding

CredX is a leading credit card provider that gets thousands of credit card applications every year. But in the past few years, it has experienced an increase in credit loss. The CEO believes that the best strategy to mitigate credit risk is to acquire the right customers.

## Objective

To help CredX identify the right customers using predictive models. Using past data of the bank’s applicants, we need to determine the factors affecting credit risk, create strategies to mitigate the acquisition risk and assess the financial benefit of our project. 

##Understanding the data

There are two data sets in this project: demographic and credit bureau data.  
- Demographic/application data: This is obtained from the information provided by the applicants at the time of credit card application. It contains customer-level information on age, gender, income, marital status, etc.
- Credit bureau: This is taken from the credit bureau and contains variables such as 'number of times 30 DPD or worse in last 3/6/12 months', 'outstanding balance', 'number of trades', etc.

Both files contain a performance tag, which indicates whether the applicant has gone 90 days past due (DPD) or worse in the past 12 months (i.e. defaulted) after getting a credit card.

## Business Outcome

Build an application scorecard with the good to bad odds of 10 to 1 at a score of 400 doubling every 20 points.

- For the rejected population, calculate the application scores and assess the results. Compare the scores of the rejected population with the approved candidates and comment on the observations.
- On the basis of the scorecard, identify the cut-off score below which you would not grant credit cards to applicants.

You can check the code and dataset at [link](https://github.com/ankushhanda/data-science/blob/master/CredX_Scorecard)