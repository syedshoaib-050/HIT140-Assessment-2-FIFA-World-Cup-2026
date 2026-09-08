# HIT140 Foundations of Data Science - Assessment 2

## FIFA World Cup 2026 Data Analysis

This repository contains the Python notebooks and datasets used for HIT140 Foundations of Data Science Assessment 2.

## Objective 1

Four distinct statistical analysis tasks were completed.

### Task 1 - Rhythm
**Question:** Is mean top speed different between forwards and defenders?

**Data source:** FIFA World Cup 2026 Player Statistics

**Analysis:**
- Data preparation and random sampling
- Descriptive statistics
- Visualisations
- 95% confidence intervals
- Normality testing
- Welch two-sample t-test

Notebook: `Objective1/Rhythm_Task_1.ipynb`

Dataset: `datasets/Task 1.csv`

### Task 2 - Riad
**Question:** Is mean shots on target per 90 different between forwards and midfielders?

**Data source:** FBref World Cup 2026 Player Shooting Statistics

**Analysis:**
- Data preparation and sampling
- Descriptive statistics
- Visualisations
- 95% confidence intervals
- Normality testing
- Welch two-sample t-test

Notebook: `Objective1/Task2_Riad_FBref_.ipynb`

Dataset: `datasets/Task 2.csv`

### Task 3 - Shoaib
**Question:** Is mean total fouls different between regulation-time group-stage and knockout-stage matches?

**Data source:** The Stats Don't Lie World Cup 2026

**Analysis:**
- Match-level data preparation
- Extra-time match handling
- Random sampling
- Descriptive statistics
- Visualisations
- 95% confidence intervals
- Normality testing
- Welch two-sample t-test

Notebook: `Objective1/Task3_Shoaib_Fouls.ipynb`

Dataset: `datasets/Task 3.csv`

### Task 4 - Afaan
**Question:** Is mean possession percentage different between teams that reached the knockout stage and teams eliminated during the group stage?

**Data source:** FBref World Cup 2026 Squad Standard Statistics

**Analysis:**
- Team classification
- Random sampling
- Descriptive statistics
- Visualisations
- 95% confidence intervals
- Normality testing
- Welch two-sample t-test
- Effect size

Notebook: `Objective1/Task4_Afaan_Possession.ipynb`

Dataset: `datasets/Task4.csv`

## Objective 2

### Linear Regression 2.1

A linear regression model was developed to predict goal difference between two opposing teams.

- 104 match observations
- Exactly 8 explanatory variables
- Only pre-match information used
- Chronological train/test split
- MAE, RMSE and R-squared evaluation
- Actual versus predicted analysis
- Residual analysis

Notebook: `Objective2/Objective_2_L1.ipynb`

Dataset: `datasets/Objective 2.csv`

### Linear Regression 2.2

A second linear regression model was developed to predict the number of goals scored by a team in a match.

- 208 team-match observations
- Exactly 8 explanatory variables
- Only pre-match information used
- 166 training observations
- 42 testing observations
- Baseline comparison
- MAE, RMSE and R-squared evaluation
- Residual analysis

Notebook: `Objective2/Objective2_L2.ipynb`

Dataset: `datasets/Objective 2.csv`

## Software

Python was used for all data wrangling, statistical analysis, visualisation and regression modelling.

Main libraries:
- pandas
- numpy
- matplotlib
- scipy
- scikit-learn
