# Credit-Risk-Modeling-in-Python
## Introduction
The dataset contains all available data for more than 800,000 consumer loans issued from 2007 to 2014 by Lending Club: a large US peer-to-peer lending company. There are several different versions of this dataset. We have used a version available on kaggle.com. You can find it here: (https://www.dropbox.com/scl/fi/rzqaawjqwt4qe3rmnnxiw/loan_data_2007_2014.csv?rlkey=a5y6ojznit1ozu8fwt0m7w11w&e=1&dl=0)
We divided the data into two periods because we assume that some data are available at the moment when we need to build Expected Loss models, and some data comes from applications after. Later, we investigate whether the applications we have after we built the Probability of Default (PD) model have similar characteristics with the applications we used to build the PD model.

In this project, we are going to focus on the general case: Enough data are available for implementing a traditional statistical methodology to build credit risk models. Our goal is to learn how to build statistical models for estimating EL.
We will create 3 different models:
- PD (Probability of Default) - showing a customer not repaying their debt in full or on time.
- LGD (Loss Given Default) - showing the proportion of an exposure a company loses when a customer defaults.
The proportion of the total exposure that cannot be recovered by the lender once a default has occured.
- EAD (Expoosure at Default) - showing the total loss in terms of amount of money the bank is exposed to if a customer defaults.
