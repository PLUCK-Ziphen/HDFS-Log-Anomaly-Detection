# HDFS Log Anomaly Detection Using Machine Learning

A machine learning project focused on analyzing Hadoop Distributed File System (HDFS) logs and identifying abnormal system behavior through data analysis and predictive modeling.

## Overview

Modern distributed systems generate large volumes of log data, making manual identification of system anomalies difficult and time-consuming.

This project explores the use of machine learning techniques to detect anomalous behavior in HDFS logs. It uses the HDFS log anomaly detection dataset to understand event patterns, analyze normal and abnormal system activities, and develop models for automated anomaly detection.

The initial development phase focuses on dataset exploration, statistical analysis, and visualization. Further development will involve preprocessing, feature engineering, model training, and performance evaluation.

## Dataset

The project uses the HDFS log anomaly detection dataset.

Dataset characteristics:

- Approximately 575,000 log instances.
- 32 columns in the analyzed dataset.
- 29 event-related features (E1–E29).
- Normal and anomalous log classifications.
- Approximately 97% normal instances and 3% anomalous instances.

The dataset is not included in this repository because of its large size.

This project uses the HDFS_v1 dataset provided by Loghub.
Download: https://zenodo.org/records/8196385/files/HDFS_v1.zip?download=1

Source: https://github.com/logpai/loghub

The dataset is not included in this repository due to its size.

Please refer to the original Loghub repository for dataset usage conditions and citation requirements.
Users should obtain the dataset from its original source and configure the appropriate file paths before running the notebook.

### Reference

Xu, W., Huang, L., Fox, A., Patterson, D., and Jordan, M.
"Detecting Large-Scale System Problems by Mining Console Logs."
SOSP, 2009.

## Current Implementation

The following components have been completed:

- Dataset loading and inspection.
- Exploratory Data Analysis (EDA).
- Dataset structure and statistical analysis.
- Missing-value analysis.
- Duplicate record analysis.
- Normal versus anomalous class distribution.
- Event frequency analysis.
- Data visualization and distribution analysis.

## Planned Development

The project is currently under development.

Future implementations include:

- Data preprocessing and cleaning.
- Feature selection and engineering.
- Train-test dataset splitting.
- Machine learning model implementation.
- Comparison of different classification algorithms.
- Model evaluation using precision, recall, F1-score, and ROC-AUC.
- Confusion matrix and performance visualization.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Structure

HDFS-Log-Anomaly-Detection/
│
├── notebooks/
│   └── HDFS_Log_Anomaly_Detection.ipynb
│
├── data/
│   └── (Dataset stored locally, not tracked by Git)
│
├── README.md
├── requirements.txt
└── .gitignore

## Getting Started

### 1. Clone the repository

Clone this repository to your local machine.

### 2. Install dependencies

Install the required Python libraries using the requirements file.

### 3. Obtain the dataset

Download the HDFS dataset from its original source. Place the required dataset files in the appropriate local directory.

### 4. Open the notebook

The notebook can be opened using Google Colab or a local Jupyter Notebook environment.

Configure the dataset paths according to your environment before executing the cells.

## Project Status

**Active Development**

This repository documents the ongoing development of an HDFS log anomaly detection system. The current version focuses on exploratory data analysis, with machine learning implementation and evaluation planned for subsequent stages.

## License

To be determined.