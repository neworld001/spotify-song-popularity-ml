# Predicting Song Popularity Using Machine Learning

This project develops machine learning models to predict song popularity using a dataset of **26,000+ Spotify tracks**. The goal is to identify which audio characteristics and listener behavioral signals are most predictive of a song’s success.

The project demonstrates an end-to-end machine learning workflow including data preprocessing, exploratory data analysis, feature engineering, model development, and model evaluation.

---

# Problem Statement

Music streaming platforms contain large volumes of track-level data describing both audio characteristics and user engagement signals. Understanding how these features influence popularity can support:

- recommendation system design
- playlist curation strategies
- content promotion and marketing decisions
- behavioral pattern modeling in digital media platforms

This project builds classification models to predict whether a track will achieve high popularity based on its audio attributes.

---

# Dataset

The dataset contains **26,000+ Spotify tracks** with audio features extracted through the Spotify API.

Key features include:

| Feature | Description |
|------|-------------|
| danceability | How suitable a track is for dancing |
| energy | Perceptual measure of intensity and activity |
| loudness | Overall loudness of the track |
| tempo | Estimated tempo in beats per minute |
| valence | Musical positiveness conveyed by a track |
| acousticness | Likelihood the track is acoustic |
| speechiness | Presence of spoken words |

These attributes capture structural and behavioral signals that may influence listener engagement and song popularity.

---

# Project Workflow

The project follows a typical supervised machine learning pipeline:

1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering and correlation analysis  
4. Model training and hyperparameter configuration  
5. Model evaluation and validation  

---

# Exploratory Data Analysis

Exploratory analysis was conducted to understand relationships between audio features and popularity. Visualizations and statistical analysis revealed several key correlations:

- Tracks with higher **danceability** tend to exhibit stronger popularity signals
- **Energy and loudness** show positive association with engagement metrics
- Certain feature combinations appear to characterize highly popular tracks

Correlation heatmaps and feature distributions were used to guide feature selection for model training.

---

# Feature Engineering

Several transformations were applied to prepare features for machine learning models:

- normalization of continuous audio attributes
- removal of highly correlated redundant features
- transformation of popularity into a classification target
- selection of high-signal predictors based on correlation analysis

These steps helped improve model stability and predictive performance.

---

# Machine Learning Models

Two supervised learning models were implemented using **scikit-learn**:

### Logistic Regression
A linear classification model used as a baseline to evaluate predictive power of the audio features.

### Decision Tree Classifier
A non-linear model capable of capturing complex interactions between musical attributes.

---

# Model Evaluation

Model performance was evaluated using multiple validation techniques:

- **Train-test split validation**
- **Cross-validation**
- **Accuracy**
- **ROC-AUC**

The models achieved approximately:

**78% classification accuracy**

in predicting song popularity.

---

# Key Findings

The analysis identified several features that strongly influence predicted popularity:

- danceability
- energy
- loudness

These features appear to capture listener engagement patterns and musical characteristics associated with successful tracks.

---

# Tech Stack

Python  
pandas  
numpy  
scikit-learn  
matplotlib  
seaborn  
Jupyter Notebook  

---

# Future Improvements

Possible extensions of the project include:

- gradient boosting models (XGBoost / LightGBM)
- deeper feature engineering using Spotify metadata
- model interpretability analysis (SHAP values)
- integration with recommendation system pipelines

---

# Key Takeaway

This project demonstrates how machine learning techniques can be applied to behavioral and audio feature data to model popularity patterns in music streaming platforms.
