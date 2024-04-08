# Foray NL Fungal Diversity Analysis

This repository contains the code and documentation for analyzing fungal diversity data collected by Foray NL, a non-profit organization conducting amateur mushroom forays in Newfoundland and Labrador. The analysis aims to address the following objectives:

<a href="https://nlmushrooms.ca/">
  <img align="right" width="100" height="100" src="https://nlmushrooms.ca/_wp_generated/wpb8d4985e_05_06.jpg">
</a>
<p align="left">
1. Identifying hotspots of fungal diversity in the province. </br>
2. Understanding fungal diversity patterns in space and time. </br>                                  
3. Comparing diversity at the same locations across different years. </br>
</p>



   

## Dataset Exploration & Cleaning

- Load and assess the dataset structure and quality.
- Filter out irrelevant columns and retain those related to fungal diversity.
- Handle missing values appropriately.
<a href="https://nlmushrooms.ca/">
  <img align="right" width="100" height="100" src="https://nlmushrooms.ca/_wp_generated/wp872fe8a4_05_06.jpg">
</a>
## Data Visualization

- Create scatter plots of latitude and longitude to visualize geographical distribution.
- Utilize matplotlib and seaborn libraries for plotting.



## Identifying Hotspots or Diversity Patterns

- Analyze visualization plots to identify clusters or concentrations of data points.
- Infer hotspots based on areas with dense concentrations of data points.

## Applying Machine Learning

- Apply supervised machine learning classifier algorithms for prediction.
- Perform cross-validation and evaluate model predictions.

## Methodology for Objective 3 (Machine Learning Integration)

Objective 3 involves comparing diversity at the same locations across different years, making it suitable for applying supervised machine learning techniques. Here's a summary of the approach:

1. **Clear Objective**: The goal is to compare diversity levels at the same locations but in different years.
2. **Structured Data**: The dataset likely has a structured format, making it suitable for supervised learning.
3. **Predictive Modeling**: Various predictive modeling techniques will be applied to learn patterns and make predictions.
4. **Evaluation Metrics**: Metrics like mean squared error (MSE) or correlation coefficient will assess prediction accuracy.
5. **Validation Techniques**: Cross-validation will validate model performance.

## Summary of Results
<a href="https://nlmushrooms.ca/">
  <img align="right" width="100" height="100" src="https://nlmushrooms.ca/_wp_generated/wp11143d05_05_06.jpg">
</a>

- Geographical Hotspots: Identified using scatter plots and heatmaps.
- Habitat Influence: Primary habitats supporting fungal diversity highlighted.
- Temporal Patterns: Analysis of event date distribution and dominant fungal families.
- Spatial-Temporal Dynamics: Dynamic changes in species diversity observed.
- Machine Learning Integration: Foundation for future predictive modeling.


For more detailed analysis and results, refer to the Jupyter notebooks and documentation provided in this repository.

## Dataset Source
- [Foray NL Website](http://www.nlmushrooms.ca/index.html).
