# Predicting Song Popularity Using Machine Learning

This project analyzes **26,000+ Spotify tracks** to predict song popularity using machine learning models built with Python and scikit-learn.

## Overview

The goal of this project is to identify which **audio and listener behavioral features** are most predictive of song popularity. The workflow includes data preprocessing, exploratory analysis, feature engineering, model training, and evaluation.

## Dataset

The dataset contains track-level Spotify audio features such as:

- danceability
- energy
- loudness
- tempo
- valence
- acousticness
- speechiness

These features were used to model popularity patterns across a large music dataset.

## Methods

Implemented machine learning classification models using **scikit-learn**, including:

- Logistic Regression
- Decision Tree Classifier

## Workflow

- Cleaned and prepared Spotify track data
- Performed exploratory data analysis on audio features
- Conducted feature engineering and correlation analysis
- Trained classification models to predict song popularity
- Evaluated performance using cross-validation, ROC-AUC, and accuracy

## Results

The models achieved approximately **78% prediction accuracy** and highlighted key drivers of popularity, including:

- danceability
- energy
- loudness

## Tech Stack

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## Key Takeaway

This project demonstrates an end-to-end machine learning workflow on real-world behavioral and audio data, from feature analysis through model evaluation.
