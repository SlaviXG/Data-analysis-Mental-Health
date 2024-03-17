# Mental Health Analysis

## Overview

This project aims to explore the relationship between anxiety disorder prevalence and the provision of mental health treatment across various countries. It investigates trends over time and examines the distribution of different types of treatments.

## Dataset

### Anxiety Disorder Prevalence and Treatment Gap
- Dataset Source: [Kaggle](https://www.kaggle.com/datasets/imtkaggleteam/mental-health)
- This dataset includes information on anxiety disorder prevalence and the treatment gap across multiple countries.

### Mental Health Treatment Types
- Dataset Source: [Kaggle](https://www.kaggle.com/datasets/imtkaggleteam/mental-health)
- This dataset provides insights into the distribution of different types of mental health treatments, including potentially adequate treatment, untreated cases, and other treatment methods.

## Analysis

### Relationship Between Year and Anxiety Disorders in the UK (1990-2019)
- Conducted Simple Linear Regression, Polynomial Regression, and Time Series Regression to analyze the relationship between the year and the share of the population with anxiety disorders in the UK.
- Explored violin plots and Spearman correlation to understand the data distribution and correlation between variables.
- Visualized the regression results and model diagnostics using scatter plots, residual plots, and residual normal quantile plots.

### Distribution of Mental Health Treatment Types Across Countries
- Investigated the distribution of different types of mental health treatments, including potentially adequate treatment, untreated cases, and other treatment methods.
- Utilized boxplots and bar charts to visualize the distribution of treatment types across various countries.

## Dependencies
numpy==1.26.4
pandas==2.2.1
matplotlib==3.8.3
matplotlib-inline==0.1.6
seaborn==0.13.2
statsmodels==0.14.1
scikit-learn==1.4.1.post1
plotly==5.19.0

## Usage
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the provided Python scripts to analyze the datasets and visualize the results.

