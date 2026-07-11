# RiskLab Analysis Project

## Goal
Build a Python risk analytics toolkit demonstrating statistical analysis, financial risk modelling, and predictive methods.

## Project Structure
Part 1 — Insurance Risk Module
- Data overview
- Cleaning
- Missing values
- Summary statistics
- Claim distributions
- Visualisations
- Claim frequency modelling
- Claim severity modelling
- Distribution fitting
- Expected loss calculation

Part 2 - Market Risk Module
- Download price data
- Calculate returns
- Volatility
- Correlation
- Portfolio analysis
- Historical VaR
- Monte Carlo VaR

Part 3 - Prediction Module
Insurance: Predict claim cost.

#### Models:

Baseline: Linear regression

Advanced: Random forest

Evaluate:
- MAE
- RMSE
- R²

## Current stage
- Setting up project structure
- Planning first simulation model

## Tools & Technologies

### Programming Language
- [Python](https://www.python.org/)

### Data Analysis & Manipulation
- [Pandas](https://pandas.pydata.org/docs/)
- [NumPy](https://numpy.org/doc/)

### Statistical Analysis
- [SciPy](https://docs.scipy.org/doc/scipy/)
- [Statsmodels](https://www.statsmodels.org/stable/index.html)

### Data Visualisation
- [Matplotlib](https://matplotlib.org/stable/)
- [Seaborn](https://seaborn.pydata.org/)
- [Plotly](https://plotly.com/python/)

### Machine Learning
- [Scikit-learn](https://scikit-learn.org/stable/)

### Development Environment
- [Jupyter Notebook](https://jupyter.org/documentation)
- [Visual Studio Code](https://code.visualstudio.com/docs)
- [Git](https://git-scm.com/doc)
- [GitHub](https://docs.github.com/)

### Future Development
- [Streamlit](https://docs.streamlit.io/)
- [Flask](https://flask.palletsprojects.com/)

## Data Source & License

This project uses the **French Motor Third-Party Liability (freMTPL2)** dataset,
obtained via Kaggle.

- **Original source:** `CASdatasets` R package by Christophe Dutang and Arthur Charpentier,
  originally compiled for *Computational Actuarial Science with R* (ed. Arthur Charpentier).
  Official repository: https://dutangc.github.io/CASdatasets/
- **License:** GPL (>= 2)
- **Accessed via:** Kaggle mirror — [https://www.kaggle.com/datasets/karansarpal/fremtpl-french-motor-tpl-insurance-claims?resource=download]
- **Citation:**
  > Dutang, C. and Charpentier, A. *CASdatasets: Insurance datasets*, R package.

The dataset contains anonymized policy-level information for approximately 680,000 French motor insurance policies, including vehicle, driver, and regional characteristics, together with claim frequency and claim severity data. No personally identifiable information is included. 

This repository is an independent educational and portfolio project intended to demonstrate actuarial and data science techniques. It is not affiliated with or endorsed by the original dataset authors. Full credit for the dataset belongs to its original creators.
