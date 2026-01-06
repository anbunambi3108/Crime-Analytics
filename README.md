# 📊 Crime Analytics

**U.S. Crime Trend Analysis Using Linear Regression**

A statistical analysis project examining how socioeconomic and demographic factors influence crime rates across U.S. states.

## 🧭 Overview

This project analyzes U.S. state-level crime data to understand how socioeconomic, demographic, and law enforcement factors relate to crime rates. Using linear regression, the analysis applies data transformation, correlation screening, and iterative model refinement to identify statistically significant predictors. The final model explains a substantial portion of crime rate variability and provides interpretable insights relevant to crime prevention and public policy.

## ✨ Key Highlights

* Built and refined multiple linear regression models to explain crime rate variation
* Applied log transformation to address non-normality in crime rate data
* Identified income inequality and youth demographics as key crime predictors
* Reduced multicollinearity through variable selection and diagnostics
* Achieved strong explanatory power with a final model R-squared of 76.49%
* Validated model assumptions using residual and autocorrelation analysis

## 🧩 Features

### Analysis Components

| Component             | Description                                     | Status   |
| --------------------- | ----------------------------------------------- | -------- |
| Data Exploration      | Distribution analysis and normalization checks  | Complete |
| Correlation Screening | Identification of high-impact predictors        | Complete |
| Regression Modeling   | Stepwise model refinement                       | Complete |
| Diagnostics           | VIF, residuals, Durbin-Watson testing           | Complete |
| Interaction Effects   | Income inequality and demographic interaction   | Complete |
| Prediction            | Crime rate estimation with confidence intervals | Complete |

## 🔬 Methodology

### 1. Data Collection

* Aggregated 1960 U.S. crime data across 47 states
* Included crime rates, policing expenditure, income metrics, education, labor data, and demographics

### 2. Exploratory Analysis

* Identified right-skewed crime rate distribution
* Applied log transformation to stabilize variance and normalize residuals
* Performed correlation analysis to shortlist predictors

### 3. Core Modeling

* Developed multiple regression models with iterative refinement
* Addressed multicollinearity using VIF analysis
* Introduced interaction terms to capture compound socioeconomic effects

### 4. Validation and Evaluation

* Assessed goodness-of-fit using R-squared and adjusted R-squared
* Verified residual independence via Durbin-Watson statistic
* Compared nested models using increase-in-R-squared testing

## 📈 Key Results

### Performance Outcomes

* Final regression model explains approximately three-quarters of crime rate variability
* Strong overall model fit with statistically significant predictors
* Stable residual behavior with acceptable autocorrelation levels

### Business and Policy Insights

* Income inequality consistently emerges as a major driver of crime rates
* Youth male population amplifies crime impact when combined with inequality
* Education and policing expenditure show meaningful but secondary influence
* Results support targeted, data-driven crime prevention strategies

## 🛠️ Technologies

### Tools

| Technology          | Purpose                                     |
| ------------------- | ------------------------------------------- |
| Minitab             | Statistical modeling and diagnostics        |
| Excel               | Data validation and prediction verification |
| Linear Regression   | Core analytical method                      |
| Statistical Testing | Model comparison and validation             |

### Libraries and Methods

```text
Linear Regression
Log Transformation
Correlation Analysis
Variance Inflation Factor (VIF)
Durbin-Watson Test
Residual Diagnostics
Interaction Term Modeling
```
## 🧠 Skills Demonstrated

* Statistical modeling and regression analysis
* Feature selection and multicollinearity handling
* Data transformation and normalization
* Model diagnostics and validation
* Translating statistical results into policy insights
* Analytical documentation and reporting

## 🚀 Getting Started

### Prerequisites

* Minitab or equivalent statistical software
* Basic understanding of regression analysis

### Usage

```bash
# Clone repository
git clone https://github.com/your-username/crime-analytics.git

# Navigate to project directory
cd crime-analytics

# Open analysis files in Minitab
```
