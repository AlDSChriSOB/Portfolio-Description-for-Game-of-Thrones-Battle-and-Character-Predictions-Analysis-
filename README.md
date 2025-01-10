# Portfolio-Description-for-Game-of-Thrones-Battle-and-Character-Predictions-Analysis-
Game of Thrones Battle and Character Predictions Analysis
This repository contains an exploratory analysis of "Game of Thrones" battle data and character predictions using various Python libraries and machine learning models. The dataset includes information on battles, character survival, and additional metadata about characters. The analysis seeks to uncover hidden patterns and provide predictions about character survival based on a variety of factors.

Table of Contents
Introduction
Dataset
Analysis
Exploratory Analysis
Predictive Modeling
Technologies
Usage
Results


Introduction
This project explores data derived from the "Game of Thrones" TV series and books, focusing on battles and character survival. Key analyses include visualizations of battle outcomes, character survival patterns, and predictive experiments using machine learning.

Dataset
The dataset used for this analysis includes:

Battles Data: Information about battles, including sizes of attacking and defending armies, outcomes, and locations.
Character Deaths Data: Data on character fates, whether they survive or die, and relevant metadata like culture and house.
Character Predictions: Predictions about whether characters will live or die, along with a set of features used for these predictions.
New Attributes in the Dataset:
defender_count – Number of major houses on the defending side
attacker_count – Number of major houses on the attacking side
att_comm_count – Number of commanders on the attacking side
no_of_books – Number of books a character appeared in

Analysis
Exploratory Analysis
Key insights include:

Impact of Army Size on Outcome: A scatter plot of attacker vs. defender size and the outcome of battles.
Major Deaths and Captures by Year: A bar plot showing the number of major deaths and captures over the years.
Survival Based on Relationships: A visualization of the relationship between a character's family ties and survival.
Predictive Modeling
A predictive model was built to assess the likelihood of character survival based on various features. This model uses:

XGBoost for classification.
Logistic Regression for binary outcomes.
Results
A Radar Chart visually represents the types of battles different kings fought as attackers and defenders.
Class Imbalance in survival predictions was addressed to ensure better model performance.

Technologies
Python Libraries:
pandas
numpy
seaborn
matplotlib
xgboost
scikit-learn
Data Visualization: Seaborn, Matplotlib, Radar Charts
