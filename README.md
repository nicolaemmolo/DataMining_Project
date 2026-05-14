# Data Mining Project

Data Mining project. Computer Science Master Degree, University of Pisa. A.Y 2024/2025


## Overview

This repository contains the code and resources for a comprehensive Data Mining project focused on the analysis of professional cycling competitions. The primary goal of this project is to analyze the dynamics of cycling races and the attributes of cyclists, leveraging machine learning and statistical methodologies to discover patterns and predict performance outcomes.

The analysis uses two main datasets comprising professional cycling races spanning several years:
1. **Cyclists Dataset**: Contains detailed characteristics and statistics of individual cyclists.
2. **Races Dataset**: Contains race-specific information, such as length, total climb, profile difficulty (e.g., flat, mountainous), and the starting list quality.

The project follows the complete Data Mining pipeline, exploring everything from initial data cleaning and dimensionality reduction to advanced clustering, classification models, and explainability techniques.


## Project Structure

The repository is structured around the 5 main tasks specified in the assignment, along with supporting directories for data and utility functions:

* **`data/`**: Contains the raw and processed datasets (Cyclists and Races) used throughout the experiments. *(Note: ensure data is unzipped here before running the notebooks)*.
* **`src/`**: Contains a single `utils.py` file with general-purpose helper functions used across multiple notebooks to avoid code duplication.
* **`TASK1/`**: Focuses on exploring data distributions, handling missing values, outlier detection (e.g., using Isolation Forest), feature engineering, and dimensionality reduction (PCA and UMAP).
* **`TASK2/`**: Applies unsupervised learning algorithms such as K-Means, DBSCAN, and Hierarchical Clustering to group similar cyclists and race profiles.
* **`TASK3/`**: Trains and evaluates predictive models to classify race outcomes or cyclist performances.
* **`TASK4/`**: Extracts frequent itemsets and association rules to find interesting relationships between race features and cyclist attributes.
* **`TASK5/`**: Uses explainable AI (XAI) techniques to interpret the decisions made by the classification models and understand the most impactful features.
* **`report.pdf`**: The final comprehensive report detailing the methodology, experiments, and conclusions of the project.


## Authors
[Simone Marzeddu](https://github.com/SimoneMarzeddu) \
[Nicola Emmolo](https://github.com/nicolaemmolo) \
[Jacopo Raffi](https://github.com/JacopoRaffi) 
