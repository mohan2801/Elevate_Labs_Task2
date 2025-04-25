Titanic Dataset Analysis - Exploratory Data Analysis (EDA):
This repository contains an in-depth analysis of the Titanic dataset using Python. The goal is to perform Exploratory Data Analysis (EDA) to uncover patterns, handle missing data, and visualize relationships between variables.

Dataset Overview:
The Titanic dataset contains passenger information from the ill-fated voyage, including survival status, age, gender, ticket class, fare, and embarkation port.

Analysis Steps:
1. Data Loading & Initial Inspection
The dataset was loaded using Pandas to examine its structure.

Basic checks were performed to understand the data dimensions, missing values, and column types.

2. Handling Missing Values
The Cabin column was dropped due to excessive missing data.

Missing Age values were filled with the median age for robustness against outliers.

Missing Embarked values were replaced with the most frequent port (mode).

3. Encoding Categorical Variables
The Sex column was converted to numerical values (0 for male, 1 for female).

The Embarked column was mapped to numerical codes (C=0, Q=1, S=2) for analysis.

4. Data Visualization
Survival Count: A bar plot showing the distribution of survivors vs. non-survivors.

Age Distribution: A histogram displaying passenger age frequencies.

Visualizing all Numerical Columns using Histogram and Boxplots

Fare vs. Survival: A boxplot comparing fare distributions between survivors and non-survivors.

Correlation Matrix: A heatmap illustrating relationships between numerical features.

5. Key Observations made from analysis
Survival Rate: ~38% survived.

Gender Impact: Females had higher survival rates.

Fare & Class: Higher fares (1st class) had better survival odds.

Age: Most passengers were between 20-40 years old.



Tools Used:
Python (Pandas, Seaborn, Matplotlib)
