# 🏡 Boston Housing Price Analysis Using Multiple and Robust Regression

### Regression Analysis & Predictive Analytics | 2026

Developed by **Florence Elaine G. Soleño**

---

## Project Overview

Housing prices are influenced by a combination of property characteristics, environmental conditions, neighborhood accessibility, and socioeconomic factors. Understanding how these variables contribute to differences in property values is essential for informed urban planning, housing policy, and real estate investment decisions.

This project applies **multiple linear regression and robust regression techniques** to analyze housing values across neighborhoods in the Boston metropolitan area using historical housing data derived from U.S. Census records.

The analysis begins with exploratory data analysis and preprocessing, followed by testing key regression assumptions, including normality and homoscedasticity. When these assumptions are violated, **robust regression using the Hampel estimator** is introduced to reduce the influence of outliers and assess the reliability of model estimates.

The goal is to **identify key factors associated with housing prices, evaluate regression model reliability, and provide data-driven insights for urban planning and housing valuation.**

## Dataset Information

This project uses the *Boston Housing* dataset, originally compiled from housing and neighborhood information in the Boston metropolitan area.

- **Objective:** Analyze and explain variations in median housing values
- **Unit of Analysis:** Census tracts in the Boston metropolitan area
- **Dataset Size:** 506 observations
- **Predictor Variables:** 13 housing, environmental, accessibility, and socioeconomic indicators
- **Target Variable:** Median Value of Owner-Occupied Homes (MEDV), expressed in thousands of US dollars

### Key Dataset Features

- **Housing Characteristics:** Average number of rooms (RM), proportion of older housing units (AGE)
- **Environmental Conditions:** Nitric oxide concentration (NOX), proximity to industrial areas (INDUS)
- **Neighborhood Accessibility:** Distance to employment centers (DIS), highway accessibility (RAD), Charles River proximity (CHAS)
- **Economic Indicators:** Crime rate (CRIM), property tax rate (TAX), residential zoning (ZN)
- **Socioeconomic Factors:** Pupil-teacher ratio (PTRATIO), historical demographic variable (B), lower-status population percentage (LSTAT)

*Note: The dataset contains historical socioeconomic variables, including B and LSTAT, that reflect outdated and potentially discriminatory classifications. These variables require careful interpretation and should not be treated as appropriate criteria for modern housing or investment decisions.*

### Dataset Source & Citation

The Boston Housing dataset is associated with the research of Harrison and Rubinfeld (1978), which examined housing prices and environmental factors in the Boston metropolitan area.

Harrison, D., & Rubinfeld, D. L. (1978). Hedonic housing prices and the demand for clean air. *Journal of Environmental Economics and Management, 5*(1), 81–102. https://doi.org/10.1016/0095-0696(78)90006-2

## Regression Analysis Implementation

### Exploratory Data Analysis

The project examines the distribution and relationships of housing variables through:

- Descriptive statistical analysis
- Data quality assessment and preprocessing
- Examination of variable distributions
- Identification of potential outliers
- Analysis of relationships between housing characteristics and median property values

### Regression Techniques

Two regression approaches are explored:

- **Multiple Linear Regression** – Estimates relationships between housing values and multiple explanatory variables using ordinary least squares (OLS).
- **Robust Regression (Hampel Estimator)** – Applies a robust estimation approach to reduce the influence of extreme observations and improve the stability of regression estimates.

### Regression Diagnostics

The analysis evaluates key statistical assumptions, including:

- **Normality of Residuals** – Examines whether model residuals approximately follow a normal distribution.
- **Homoscedasticity** – Assesses whether residual variance remains relatively constant across fitted values.
- **Outlier Influence** – Investigates whether extreme observations disproportionately affect regression estimates.
- **Model Interpretation** – Examines coefficient estimates and statistical significance to understand relationships between predictors and housing values.

## Key Findings & Insights

Based on the regression analysis, several factors emerged as relevant to understanding differences in Boston housing values.

### Housing Characteristics

The **average number of rooms per dwelling** emerged as an important positive predictor of median housing values, suggesting that larger residential properties tend to be associated with higher valuations.

### Property Taxes and Education

Higher property tax rates and pupil-teacher ratios were associated with lower housing values in the fitted analysis, highlighting the relevance of local fiscal and educational conditions to neighborhood valuation.

### Environmental and Location Factors

The analysis suggested that industrial proximity alone may not fully explain differences in housing prices, emphasizing the importance of considering environmental conditions, including pollution levels, alongside location characteristics.

### Robust Regression

The application of the **Hampel estimator** provided an alternative approach for analyzing housing prices when outliers and violations of regression assumptions raised concerns about the reliability of ordinary least squares estimates.

*These findings describe statistical associations within the historical dataset and should not be interpreted as evidence of causation or current Boston housing market conditions.*

## Technologies Used

- **Python** – Statistical analysis and regression modeling
- **Jupyter Notebook** – Data exploration, analysis, and documentation
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical computations
- **Statsmodels** – Multiple linear regression, robust regression, and statistical diagnostics
- **Matplotlib / Seaborn** – Exploratory data analysis and statistical visualization

## Project Significance

This project demonstrates how **statistical regression techniques can support housing market analysis and urban planning** by identifying relationships between property values and neighborhood characteristics.

Through regression diagnostics and robust estimation, the analysis highlights the importance of evaluating statistical assumptions and addressing influential observations when interpreting model results.

The findings provide a historical case study of how housing characteristics, environmental conditions, and local socioeconomic indicators relate to property valuation.

Although the Boston Housing dataset is widely used for educational purposes, its historical nature and problematic socioeconomic variables limit its suitability for contemporary housing policy or real-world valuation without additional data and validation.

## References

- Alonso, W. (1964). *Location and land use: Toward a general theory of land rent*. Harvard University Press.

- Black, S. E. (1999). Do better schools matter? Parental valuation of elementary education. *The Quarterly Journal of Economics, 114*(2), 577–599. https://doi.org/10.1162/003355399556070

- Harrison, D., & Rubinfeld, D. L. (1978). Hedonic housing prices and the demand for clean air. *Journal of Environmental Economics and Management, 5*(1), 81–102. https://doi.org/10.1016/0095-0696(78)90006-2

- Jin, S., Ge, Y., & Long, Y. (2024). Understanding the effects of socioeconomic factors on housing price appreciation. *Cities, 149*, 105028. https://doi.org/10.1016/j.cities.2024.105028

- Oates, W. E. (1969). The effects of property taxes and local public spending on property values: An empirical study of tax capitalization and the Tiebout hypothesis. *Journal of Political Economy, 77*(6), 957–971. https://doi.org/10.1086/259584

- Rosen, S. (1974). Hedonic prices and implicit markets: Product differentiation in pure competition. *Journal of Political Economy, 82*(1), 34–55. https://doi.org/10.1086/260169


*Academic Project | Regression Analysis & Predictive Analytics | 2026*



*Understanding housing values through statistical analysis for informed urban planning and decision-making.*
