Cardiovascular Disease Prediction Classification

This repository contains a project focused on predicting cardiovascular disease using classification techniques. The project aims to analyze a dataset containing various attributes related to individuals' health and build a model that can accurately classify whether a person is at risk of cardiovascular disease or not.

Table of Contents

Introduction
Dataset
Project Structure
Dependencies
Getting Started

Introduction

Cardiovascular disease is a major health concern globally and early detection plays a crucial role in preventing complications. This project focuses on using machine learning techniques to predict the likelihood of an individual having cardiovascular disease based on various health-related attributes such as age, gender, blood pressure, cholesterol levels, etc. By analyzing the dataset and building a predictive model, we aim to assist in identifying individuals who may require further medical attention or lifestyle interventions.

Dataset

The dataset used in this project is a collection of health-related attributes obtained from source. It includes the following features:

age: Age of the individual in years
gender: Gender of the individual (0: female, 1: male)
height: Height of the individual in centimeters
weight: Weight of the individual in kilograms
systolic_bp: Systolic blood pressure of the individual in mmHg
diastolic_bp: Diastolic blood pressure of the individual in mmHg
cholesterol: Cholesterol level of the individual (1: normal, 2: above normal, 3: well above normal)
glucose: Blood glucose level of the individual (1: normal, 2: above normal, 3: well above normal)
smoking: Smoking status of the individual (0: non-smoker, 1: smoker)
alcohol: Alcohol consumption status of the individual (0: non-drinker, 1: drinker)
active: Physical activity level of the individual (0: inactive, 1: active)
cardio: Presence or absence of cardiovascular disease (0: absence, 1: presence)

Project Structure

The project repository has the following structure:
├── data/
│   ├── cardio_data.csv          # Cardiovascular disease dataset (not included in this repo)
│   └── ...
├── notebooks/
│   ├── Cardio_Disease_Prediction.ipynb         # Jupyter Notebook with classification code
│   └── ...
├── README.md                    # Project README file
└── ...

The data directory should contain the cardiovascular disease dataset in CSV format. Please obtain the dataset from Almabetter and place it in this directory before running the code.
The notebooks directory contains a Jupyter Notebook used for data preprocessing, model training, and evaluation.
The README.md file provides an overview of the project, instructions, and details about the dataset.

Dependencies

The following dependencies are required to run the code:

Python 3.x
Jupyter Notebook
pandas
numpy
scikit-learn
matplotlib
seaborn

Getting Started

To get started with this project, follow these steps:
Clone the repository to your local machine or download the project files.
Obtain the cardiovascular disease dataset from this repository.
Install the required dependencies using the instructions provided in the Dependencies section




