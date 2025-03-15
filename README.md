# Exploratory Data Analysis (EDA) on White Wine Quality Dataset

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the White Wine Quality dataset. The dataset contains physicochemical properties of white wine samples and their corresponding quality scores. The goal of this analysis is to understand the data, identify patterns, detect outliers, and prepare it for further predictive modeling.

## Dataset Information
The dataset consists of 12 attributes:

### Input Variables (Physicochemical Tests)
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

### Output Variable (Sensory Data)
12. Quality (score between 0 and 10)

## Data Cleaning and Preprocessing
- Removed duplicate records to ensure data integrity.
- Checked for and handled missing values (if any).
- Converted data types where necessary for better analysis.

## Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Summary statistics such as mean, median, standard deviation, and distribution of variables.
- **Data Visualization**:
  - Histograms to understand the distribution of numerical variables.
  - Box plots to detect outliers in different attributes.
  - Correlation heatmap to analyze relationships between variables.
  - Scatter plots to observe trends between features and wine quality.
  - Pair plot to visualize pairwise relationships between numerical features.

## Observations
- Certain attributes like alcohol content and volatile acidity have a significant correlation with wine quality.
- The dataset is imbalanced, with most samples having a normal quality score.
- Some outliers were identified in residual sugar and total sulfur dioxide.

## Tools and Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn


## Future Work
- Implement feature selection techniques to improve predictive modeling.
- Apply machine learning models to predict wine quality.
- Investigate additional preprocessing techniques such as normalization and scaling.



