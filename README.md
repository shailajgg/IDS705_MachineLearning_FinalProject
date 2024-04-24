# Predicting NCAA Basketball Tournament Outcomes

## Overview
This repository contains code and documentation for a comprehensive study on predicting game outcomes in the NCAA Basketball Tournament, popularly known as March Madness. Leveraging machine learning techniques, extensive feature engineering, and meticulous model evaluation, this study aims to forecast winners and losers in both the men's and women's tournaments with a high degree of accuracy.

## Contents
- Code: This directory houses Python scripts responsible for data preprocessing, feature engineering, model training, and evaluation.
- Data: Contains datasets sourced from the March Machine Learning Mania 2024 Kaggle competition. These datasets encompass detailed information on team performance, tournament seeding, and external ranking systems.
- Documentation: Includes a detailed report of the study, featuring an abstract, introduction, background, experimental design, results, conclusions, and references.
- ReadMe.md: This file provides an overview of the repository's contents and guidance on usage.

## Getting Started
1. **Clone the Repository:**
```bash
git clone <repository_url>
```

## Usage


`Data Preprocessing:` Utilize provided scripts to clean and preprocess datasets, handling missing values, removing duplicates, and standardizing team names and IDs.

`Feature Engineering:` Leverage feature engineering scripts to create various features from regular season data, opponent averages, team metrics, tournament seed, win ratio, seed difference, and team quality.

`Model Training and Evaluation:` Experiment with different machine learning algorithms such as Logistic Regression, Random Forest, SVM, and XGBoost for model training and evaluation. Compare their performance using metrics like accuracy, AUC, and log-loss.
Documentation: Refer to the detailed report in the Documentation directory for insights into the study's methodology, findings, and conclusions.

# Experimentation and Ranking System

## Experimentation Overview
This repository contains code and documentation for a comprehensive study on predicting game outcomes in the NCAA Basketball Tournament. Leveraging data from the March Machine Learning Mania 2024 Kaggle competition, the experimentation process includes:

1. **Feature Engineering**: Generating various features from regular season data to establish a baseline model. This involves creating features such as team averages, opponent averages, team metrics, tournament seed, win ratio, seed difference, and team quality.

2. **Feature Selection of Outside Metrics**: Evaluating the efficacy of additional features created from different sources. The features tested include ordinal ranking, FiveThirtyEight Elo model, and a composite ranking model that integrates mean ordinal rankings with Elo ratings.

3. **Model Evaluation and Selection**: Assessing different machine learning algorithms (Logistic Regression, Random Forest, SVM, and XGBoost) to determine the most effective model for predicting game outcomes. The evaluation criteria include accuracy and area under the ROC curve (AUC).

4. **Feature Importance Analysis**: Analyzing the importance of each feature in the selected model to understand their contribution to prediction accuracy.

## Ranking System
In this study, we incorporate established ranking systems alongside regular season data to enhance predictive performance. The ranking systems tested include:

1. **Ordinal Ranking**: This feature contains rankings (e.g., #1, #2, #3, ..., #N) of men's teams dating back to the 2002-2003 season under various ranking system methodologies. The rankings provide insights into the relative strength of teams but do not quantify the gap between adjacent teams.

2. **FiveThirtyEight Elo Model**: The FiveThirtyEight Elo model calculates Elo ratings for teams based on historical match data and adjusts them after each match to reflect current performance levels. It offers a nuanced perspective on team strength.

3. **Composite Ranking Model**: This feature integrates mean ordinal rankings with Elo ratings, aiming to harness the strengths of various systems. By combining different dimensions of team performance, the composite ranking model provides a more comprehensive assessment of team strengths compared to relying solely on seed ranking.

The experimentation and ranking system analysis revealed that the composite ranking model yielded the highest accuracy and the lowest prediction error among all tested models. This indicates that combining different dimensions of team performance can lead to more robust predictions. The adoption of composite ranking enhances tournament predictions by integrating multiple ranking methods, including Elo rankings and systems rankings.


### Contributing
Contributions to this repository are welcome. If you have suggestions for improvement or find any issues, please open an issue or submit a pull request.


### Authors
Ayush Gupta
Cassie Kang
Shaila Janeth Güereca Guzmán


