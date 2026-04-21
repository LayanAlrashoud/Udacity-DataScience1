

# Predicting Patient Copay Using Medicare Pricing Data

## Overview

This project explores the relationship between Medicare pricing and patient copay values for new patients. The goal is to understand how pricing affects the amount a patient is expected to pay, and to build a simple model that can estimate copay based on pricing features.

---

## Motivation

Understanding patient costs is an important part of healthcare decision-making. By analyzing pricing data, we can get insights into how clinics determine copay values and whether pricing can be used to estimate patient payments.

---

## Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## Files in the Repository

* `DataScience1.ipynb` → Main notebook containing data analysis, visualizations, and modeling
* `Physical_Therapist_in_Private_Practice.csv` → Dataset used in the project


---

## Key Steps

The project follows the CRISP-DM process:

1. Data Understanding

   * Explored the dataset using summary statistics and visualizations

2. Data Preparation

   * Selected relevant features related to new patient pricing
   * Removed unnecessary columns

3. Modeling

   * Built a Linear Regression model to predict copay

4. Evaluation

   * Evaluated the model using MAE and R² score

---

## Results

The analysis showed a strong relationship between Medicare pricing and patient copay. The model achieved very high performance, which suggests that copay values are closely related to pricing features.

It was also observed that the most common pricing value (mode) plays a noticeable role in predicting the copay.


