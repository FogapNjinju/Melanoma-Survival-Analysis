# Melanoma Survival Analysis

## Project Overview
This repository contains an exploratory data analysis (EDA) of the "Survival from Malignant Melanoma" dataset, conducted as part of the 7CS039 Statistics in Data Science assessment at the University of Wolverhampton. The analysis examines patient data collected at University Hospital of Odense, Denmark from 1962-1977.

## Dataset
- **Source**: University of Wolverhampton / University Hospital of Odense, Denmark
- **Time Period**: 1962-1977
- **Observations**: 205
- **Variables**: 8 (time, status, sex, age, year, thickness, ulcer, and an index variable)

## Objectives
- Perform exploratory data analysis to understand:
  - Trends and distributions
  - Relationships between variables
  - Statistical hypothesis testing
- Generate meaningful insights about malignant melanoma survival patterns

## Tools and Libraries
- R programming language
- Key R packages:
  - `skimr`: Data summary
  - `ggplot2`: Data visualization
  - `gridExtra`: Plot arrangement
  - `dplyr`: Data manipulation
  - `patchwork`: Plot composition

## Analysis Structure
1. **Data Preparation**
   - Data type conversion for categorical variables
   - Missing value checks
2. **Summary Statistics**
   - Numerical summaries
   - Distribution analysis
3. **Visualizations**
   - Histograms for numerical variables
   - Bar plots for categorical variables
   - Boxplots for outlier detection
   - Scatter plots for correlations
   - Q-Q plots for normality checks
4. **Statistical Analysis**
   - Pearson correlation
   - Linear regression models
   - Two-sample significance tests

## Key Findings
- No missing values in the dataset
- Presence of outliers in age and thickness variables
- Weak correlations between numerical variables
- Significant differences in tumor thickness and survival time between genders
- Some non-normal residual distributions

## Recommendations
- Outlier handling for machine learning applications
- Feature selection and engineering
- Consider regularization techniques
- Potential dataset expansion for improved modeling

## Usage
To reproduce the analysis:
1. Ensure R and required packages are installed
2. Load the melanoma dataset
3. Run the R Markdown document (`7CS039_Assessment_Statistic_In_Data_Science.html`)

## Author
Njinju Zilefac Fogap

## License
This project is for educational purposes as part of the University of Wolverhampton's 7CS039 module assessment.
