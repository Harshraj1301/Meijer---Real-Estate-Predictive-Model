# Advanced Real Estate Analytics for Retail: Determining Express Locations

This project presents a comprehensive study on developing a predictive analytics model to identify the most profitable locations for new convenience store outlets within a large retail chain. It incorporates both proprietary data from the retail chain and public domain data, including demographic insights and competitor analysis.


## Table of Contents
- [Project Overview](#project-overview)
- [Introduction](#introduction)
- [Literature Review](#literature-review)
- [Data](#data)
- [Methodology](#methodology)
- [Model](#model)
- [Results](#results)
- [Conclusions](#conclusions)
- [Assumptions and Limitations](#assumptions-and-limitations)
- [AI Research Tool Reflection](#ai-research-tool-reflection)
- [References](#references)

## Project Overview

Developed a predictive analytics model to identify the most profitable locations for new convenience store outlets within a large retail chain. The model incorporates both proprietary data from the retail chain and public domain data, including demographic insights and competitor analysis.

## Introduction

In the competitive landscape of the retail industry, the strategic selection of store locations is crucial for business success. This project aims to employ predictive analytics and advanced data science techniques to refine the process of retail site selection, providing retail chains with a powerful tool to enhance their market penetration and profitability.

## Literature Review

The literature review encompasses an array of scholarly works that delve into various dimensions of retail analytics, each contributing valuable insights pertinent to the development of a scoring algorithm for retail site selection. These works collectively provide a multi-faceted understanding of retail dynamics, from historical methodologies to modern analytical approaches.

### Summary of Key Studies
- **Historical Methodologies:** Applebaum (1966) presents a pioneering exploration of retail site selection emphasizing demographic considerations and traffic patterns.
- **Modern Analytical Techniques:** Quang Thai et al. (2015) demonstrate the use of web scraping and API services to optimize the distribution routes for convenience stores.
- **Customer Satisfaction:** Udokwu et al. (2020) assess techniques for capturing customer satisfaction data using social media and review websites.
- **Spatial Analysis:** Aboulola (2017) highlights the strategic importance of GIS and multi-criteria decision-making models in retail site selection.

## Data

This research focused on leveraging publicly available data meticulously gathered through web scraping techniques and API integrations. The dataset includes variables critical to retail site selection such as traffic volume, distance to highways, and proximity to key amenities including groceries, restaurants, and other local services.

### Data Categories
- **Geospatial Data:** Traffic volume, distance and duration to highways and nearby places.
- **Customer Data:** County demographics such as population, number of households, income levels, household value, age, and gender.

## Methodology

The methodology employs a rigorous analytical framework to evaluate potential locations for retail expansion. It is structured into distinct phases: data collection, data preprocessing, exploratory data analysis (EDA), model building, and deployment with a continuous feedback loop for improvement.

### Key Steps
1. **Data Collection:** Gathering data via web scraping and APIs.
2. **Data Preprocessing:** Cleaning data, treating missing values, and removing outliers.
3. **Exploratory Data Analysis (EDA):** Identifying patterns and correlations within the data.
4. **Model Building:** Developing predictive and heuristic scoring models using advanced statistical and machine learning techniques.
5. **Performance Metrics:** Evaluating the model using RMSE, MAPE, and R^2 score.
6. **Continuous Improvement:** Iteratively refining the model based on feedback and new data.

## Model

### Predictive Model Development
- **One-Hot Encoding:** Transforming qualitative data into a suitable format for modeling.
- **Data Splitting and Scaling:** Dividing data into training and test sets and standardizing variables.
- **Feature Selection:** Using recursive feature elimination to optimize the feature set.
- **Hyperparameter Tuning:** Employing GridSearchCV to find the best hyperparameters.

### Heuristic Scoring Model
- **Categorization and Weighting:** Assigning weights to store features based on their impact on success.
- **Dynamic Scoring:** Producing a score to evaluate potential store locations.

## Results

### Model Evaluation
- **Train-Test Evaluation:** Achieved RMSE of 6335.45, MAE of 4779.50, and MAPE of 15.80%.
- **6-Fold Cross-Validation:** RMSE of 6503.98, MAE of 5062.84, and MAPE of 16.49%.

### Business Insights
- **Traffic and Proximity Analysis:** Locations with higher traffic volumes and optimal accessibility are likely to experience higher customer visits.
- **Nuanced Evaluation:** Providing a composite score that integrates quantitative traffic data and qualitative assessments of local amenities.

## Conclusions

The project demonstrates the potential for significantly improving store performance by choosing locations with high accessibility, favorable customer demographics, and positive sentiment. The model developed provides a robust tool for predicting the success of retail locations.

## Assumptions and Limitations

The study assumes the availability and accuracy of data from web scraping and free APIs. Limitations include potential data inaccuracies and the exhaustion of free API trial searches, which may affect the model's applicability in some regions.

## AI Research Tool Reflection

- **ChatGPT:** Assisted in generating code and summarizing research papers.
- **ResearchRabbit and SciSpace:** Provided related research papers and personalized recommendations.

## References

1. Forbes. (2023). "How Big Data is Shaping the Future of Retail Site Selection."
2. Gartner. (2022). "The Role of Advanced Analytics in Retail Location Decisions."
3. The Wall Street Journal. (2023). "Data-Driven Retail: The New Frontier in Store Location Strategy."
4. Applebaum, W. (1966). Methods for Determining Store Trade Areas, Market Penetration, and Potential Sales.
5. Quang Thai, L., & Pishva, D. (2015). Application of Web Scraping and Google API Service to Optimize Convenience Stores’ Distribution.
6. Udokwu, C., et al. (2020). Evaluating Technique for Capturing Customer Satisfaction Data in Retail Supply Chain.
7. Aboulola, O. I. (2017). A Literature Review of Spatial Location Analysis for Retail Site Selection.
8. Eglite, L., & Birzniece, I. (2022). Retail Sales Forecasting Using Deep Learning: Systematic Literature Review.
9. Ahmad, M. B., & Chua, F.-F. (2018). Location Analytics for Optimal Business Retail Site Selection.
10. Namangale, D. (2022). Location Analytics for Retail Property Investment- A GIS Based Approach.
11. Chen, Y.-M., et al. (2020). On a Method for Location and Mobility Analytics Using Location-Based Services.
12. Aversa, J., et al. (2018). Big Data Analytics: The New Boundaries of Retail Location Decision Making.
