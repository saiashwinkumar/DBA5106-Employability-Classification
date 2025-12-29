# DBA5106-Employability-Classification

## Overview

This project implements a classification model for predicting developer employability using survey-based profile data from a Kaggle dataset.

## Key Features

- **Built an end-to-end ML pipeline** to predict developer employability under asymmetric misclassification costs using survey-based profile data.

- **Systematically compared glassbox vs. blackbox models** across multiple skill-representation strategies and loss functions.

- **Identified log-loss logistic regression** with a bag-of-skills vectorizer as the most robust model (AUC ≈ 0.995) with cost-sensitive threshold optimization.
