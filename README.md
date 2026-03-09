# ML-fundamentals-2026

This repository contains a complete data preparation pipeline for the University of California, Irvine (UCI) Bank Marketing Dataset. The goal is to prepare the data correctly for machine learning, while explaining and justifying each step.

## Project Overview

The Bank Marketing Dataset contains data from direct marketing campaigns of a Portuguese bank. The objective is to predict whether a client will subscribe to a term deposit after being contacted.  

## Repository Contents

- `assignment_1_Alesia_Dako.ipynb` – Main Jupyter Notebook with the full pipeline and explanations  
- `assignment_1_Alesia_Dako.pdf` – PDF version of the notebook
- `archive/` – Dataset folder containing the original CSVs  
- `.gitignore` – Files ignored by git

## Features and Tasks Performed

This project includes:

- Data Loading and Exploration
- Identifying the Prediction Target
- Handling Implicit and Explicit Missing Values
- One-Hot Encoding of Categorical Variables
- Feature Scaling for Numerical Variables
- Train/Test Split
- Baseline and Imbalanced Logistic Regression Models
- Class Imbalance Handling (Class Weights & SMOTE)
- Feature Selection using RFE
- Critical discussion of design choices and pitfalls

## Requirements

To run the project locally, install the following:

```bash
pip install -r requirements.txt
