## Project Overview
This project performs Exploratory Data Analysis (EDA), Data Cleaning, Feature Engineering, and Preprocessing on the Titanic Dataset to understand the major factors affecting passenger survival and prepare the dataset for machine learning models.

---

## Objectives
- Clean and preprocess the dataset
- Handle missing values
- Perform feature engineering
- Analyze survival patterns
- Create visualizations
- Prepare data for machine learning

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Data Preprocessing

### Missing Value Handling
- Filled missing `Age` values using median
- Filled missing `Embarked` values using mode
- Dropped `Cabin` column due to excessive missing values

---

## Feature Engineering

Created new meaningful features:

| Feature | Description |
|---|---|
| Family_Size | Total family members traveling together |
| Is_Alone | Indicates whether passenger traveled alone |
| Title | Extracted titles from passenger names |
| Age_Group | Categorized passengers by age |
| Fare_Group | Categorized passengers by fare |
| Fare_Per_Person | Estimated individual fare spend |

---

# Exploratory Data Analysis (EDA)

## Univariate Analysis
Analyzed:
- Survival distribution
- Passenger class distribution
- Gender distribution
- Family size distribution
- Fare distribution

---

## Bivariate Analysis
Studied relationships between:
- Sex vs Survival
- Pclass vs Survival
- Fare vs Survival
- Age vs Survival
- Family Size vs Survival

---

## Multivariate Analysis
Explored combined effects of:
- Gender + Class + Survival
- Age + Fare + Survival
- Family Size + Class + Survival
- Fare Per Person + Gender + Survival

---

## Key Insights
- Female passengers had significantly higher survival rates
- First-class passengers survived more frequently
- Third-class passengers faced the highest mortality
- Higher fare passengers had better survival chances
- Small families survived better than large families
- Solo travelers had lower survival probability


---

## Visualizations Included
- Countplots
- Boxplots
- Histograms
- Scatterplots
- Heatmaps

---

## Project Outcome
This project demonstrates how data preprocessing, visualization, and feature engineering help uncover meaningful patterns and improve predictive analysis.

The analysis concludes that survival during the Titanic disaster was strongly influenced by:
- gender
- passenger class
- economic status
- family structure

---

