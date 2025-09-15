---
type: ProjectLayout
title: "Illness Forecasting Platform"
colors: colors-a
date: '2025-04-15'
client: "TCU Research Project"
description: >-
  A forecasting platform using Linear Regression, Random Forest, and XGBoost on CDC surveillance data, achieving 0.106 RMSE and 0.960 R² with automated data ingestion and preprocessing pipelines.
featuredImage:
  type: ImageBlock
  url: /images/projects/flu.jpg
  altText: Machine learning model performance dashboard with forecasting charts
media:
  type: ImageBlock
  url: /images/projects/ili_forecast.png
  altText: Illness forecasting platform with CDC data analysis and predictive modeling
---

## Project Overview

This illness forecasting platform was developed as a data science research project using CDC surveillance data to predict disease outbreaks and patterns. The project demonstrates advanced machine learning techniques and automated data processing capabilities for public health applications.

## Key Features

- **Multiple ML Models**: Linear Regression, Random Forest, and XGBoost implementations
- **High Performance**: Achieved 0.106 RMSE and 0.960 R² accuracy
- **Automated Data Pipeline**: Streamlined data ingestion and preprocessing
- **CDC Data Integration**: Real-time surveillance data processing
- **Reproducible Research**: Scalable and maintainable codebase

## Technologies Used

- **Machine Learning**: Scikit-learn, XGBoost, Pandas, NumPy
- **Data Processing**: Python, Matplotlib for visualization
- **Data Source**: CDC surveillance datasets
- **Deployment**: Streamlit for web interface
- **Version Control**: Git with proper documentation

## Challenges & Solutions

The biggest challenge was handling the complexity and variability of CDC surveillance data while maintaining model accuracy. I solved this by implementing robust data preprocessing pipelines and experimenting with multiple model architectures to find the optimal combination.

> "The key to successful predictive analytics is understanding that data quality and preprocessing are just as important as model selection."

## Results

- **0.106 RMSE** achieved on test dataset
- **0.960 R²** indicating excellent model fit
- **40% reduction** in manual data preparation time
- **Improved reproducibility** through automated pipelines
- **Scalable architecture** for future data sources

## Repository & Live Demo

**GitHub**: [duchieu260503/ili-forecast-app](https://github.com/duchieu260503/ili-forecast-app)
- Complete Streamlit web application
- CDC data integration and preprocessing
- 13 commits showing active development
- 1 star and active community engagement
- Jupyter Notebook (97.6%) and Python (2.4%) codebase

**Live Application**: [ili-forecast-app.streamlit.app](https://ili-forecast-app.streamlit.app/)
- Deployed Streamlit app for real-time forecasting
- Interactive model comparison interface
- Downloadable forecast results
- Public access to try the application

## Lessons Learned

This project taught me the importance of data preprocessing in machine learning applications. Working with real-world CDC data gave me valuable experience in handling messy, incomplete datasets and implementing robust preprocessing pipelines. The project also demonstrated the value of comparing multiple model architectures to find the best solution for specific data characteristics.
