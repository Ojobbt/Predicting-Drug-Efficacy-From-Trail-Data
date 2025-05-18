 Table of Contents
Project Overview

Dataset

Key Features

Tech Stack

Setup Instructions

Results

# Project Overview
The **pharmaceutical industry** often spends years and millions on developing new drugs only to face high failure rates in clinical trials. This project aims to use historical clinical trial data to:

Understand what features contribute to successful outcomes

Build predictive models that estimate trial efficacy

Support faster, data-driven decisions during drug development

# Dataset
The dataset contains anonymized records of clinical trials, including:

**Trial phases**

**Sponsor types**

**Target conditions**

**Trial durations**

**Success/failure outcomes**

*Note: Dataset was pre cleaned and processed within the notebook for modeling.*

*Key Features*
**Data Cleaning & Preprocessing**: Handling nulls, type conversions, and derived variables.

**Exploratory Data Analysis**: Visual insights into trial trends and risk factors.

**Feature Engineering**: Creation of relevant predictors like sponsor category and duration bins.

**Machine Learning Models**: Logistic Regression, Decision Trees, and Random Forests.

**Model Evaluation**: Performance comparison using accuracy, precision, and ROC curves.

*Tech Stack*
**Python**

**Apache Spark (PySpark)**

**Pandas, NumPy**

**Matplotlib, Seaborn**

**Scikit-learn**

**Databricks (Notebook Environment)**

*Setup Instructions*
Clone the repository or download the .ipynb file.

Upload the notebook to Databricks or run it locally with PySpark configured.

Install required libraries (pip install pandas numpy matplotlib seaborn scikit-learn).

Run the notebook sequentially.

Results
Models showed promising accuracy in predicting trial outcomes.

Industry sponsored trials had better success rates.

Trial phase and length were strong indicators of efficacy.




