# 17.1-Comparing-Classifiers

# Bank Marketing Campaign Analysis

## Project Overview

This project analyzes data from a Portuguese banking institution's direct marketing campaigns. The goal is to build and compare several machine learning classification models to predict whether a client will subscribe to a term deposit. By identifying customers who are most likely to subscribe, the bank can allocate its marketing resources more effectively and improve campaign conversion rates.

## Key Findings & Actionable Insights

* **Best Performing Model:** 

The **Decision Tree** model provided the best balance of performance and interpretability, achieving a **F1 score of 0.31** on the test set (vs 0.1 Baseline). This means it successfully balanced recall and precision.

* **Key Predictors of Subscription:** 
The most influential factors in a client's decision to subscribe are:
    * **Previous Campaign Outcome:** Clients who have subscribed in the past are far more likely to do so again.
    * **Month of Contact:** Campaigns run in months like March and May tend to be more successful.

* **Actionable Recommendation:** To maximize campaign ROI, marketing efforts should prioritize contacting clients who have subscribed previously and focus campaigns during the identified peak months. 
