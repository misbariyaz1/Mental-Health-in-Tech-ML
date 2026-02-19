# Mental Health in Tech: Predicting Treatment Seeking Behavior

## Overview
This repository contains code for Problem Set 1 of the SSIM916 module (Machine Learning for Social Data Science). The project explores factors associated with employees seeking treatment for mental health conditions, using survey data from the tech industry. Two machine learning models—Logistic Regression and Random Forest—are built and compared to predict whether an individual has sought mental health treatment based on demographic and workplace-related features.

## Dataset
The dataset used is the Mental Health in Tech Survey (available from Kaggle or other public sources). It contains responses from tech employees about their attitudes towards mental health, workplace benefits, family history, and whether they have sought treatment.

File: `mental-health-in-tech-survey.csv`

Key variables:
- `treatment`: outcome variable (binary: 0 = No treatment, 1 = Treated)
- Demographics: `Age`, `Gender`
- Family history: `family_history`
- Workplace factors: `benefits`, `care_options`, `anonymity`, `leave`, `work_interfere`
- Other features used in modeling: `Age` (scaled), `Gender`, `family_history`, `benefits`, `care_options`, `anonymity`, `leave`, `work_interfere`

## Research Question
Can machine learning models reliably identify employees at risk of mental health conditions using workplace and demographic data, and what does this imply for organisational policy?

## Project Structure
├── README.md
├── mental-health-in-tech-survey.csv # dataset 
└── ML_Code_Notebook.ipynb
