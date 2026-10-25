# q-fever-epidemiology-georgia

This repository contains the Python code used for the epidemiological analyses presented in an IEEE conference publication on Q fever epidemiology in Georgia.

## Project Overview

Q fever is a zoonotic disease caused by *Coxiella burnetii* and remains an important public health concern worldwide. This project investigates demographic, occupational, environmental, animal-related, and clinical factors associated with Q fever seropositivity in Georgia using statistical and machine learning methods.

## Research Objectives

- Describe the epidemiology of Q fever in Georgia.
- Identify demographic and occupational risk factors associated with Q fever seropositivity.
- Evaluate animal ownership and exposure-related predictors of infection.
- Develop and assess statistical models for identifying significant predictors of Q fever.

## Dataset

The dataset contains variables from the following domains:

- Demographic characteristics
- Geographic and residential factors
- Occupational information
- Animal ownership and animal-care practices
- Environmental and vector-related exposures
- Clinical manifestations and symptoms
- Laboratory-confirmed Q fever serology and antibody titers

## Analytical Workflow

### Data Preparation

- Data cleaning and quality assessment
- Missing data imputation using iterative imputation techniques
- Variable recoding and categorization
- Feature engineering

### Statistical Analysis

- Descriptive epidemiology
- Frequency tables and summary statistics
- Chi-square tests
- Fisher's exact tests
- Non-parametric statistical testing
- Correlation analysis using Cramér's V
- Univariate logistic regression
- Multivariable logistic regression
- Assessment of multicollinearity

### Model Evaluation

- Receiver Operating Characteristic (ROC) curve analysis
- Area Under the ROC Curve (AUC)
- McFadden's pseudo-R²
- Hosmer-Lemeshow goodness-of-fit test
- Classification performance assessment

### Data Visualization

- Correlation heatmaps
- Forest plots of adjusted odds ratios
- ROC curves
- Descriptive epidemiological visualizations

## Software and Libraries

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Scikit-learn
- Matplotlib
- Seaborn
- OpenPyXL

## Repository Contents

- Jupyter Notebook containing the complete analytical workflow
- Statistical model outputs
- Figures and visualizations
- Documentation describing methods and variables

## Data Availability

The original dataset contains research data and is not included in this repository. Only the analytical code, documentation, and selected outputs are provided.

## Publication

F. Parsayan, A. Parsayan and G. Chakhunashvili, “Epidemiological Determinants of Q Fever in Georgia Through Regression Modeling,” 2026 International Conference on Artificial Intelligence, Computer, Data Sciences and Applications (ACDSA), Boracay Island, Philippines, 2026, pp. 1-6, doi: 10.1109/ACDSA67686.2026.11467892.

## Author

Farshad Parsayan

## License

This project is distributed under the MIT License.
