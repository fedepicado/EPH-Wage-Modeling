# Statistical Regression Models applied to the analysis of the Permanent Household Survey

This project was developed as part of the course **Statistical Learning Approach** (Master’s in Data Mining and Knowledge Discovery, second semester 2023).  

The main goal is to analyze **hourly wages in Argentina** using data from the **Permanent Household Survey (EPH)**.  
Based on the available variables, the project aims to **evaluate and compare different regression models**, considering two complementary perspectives:  

1. **Explainability:** identifying relationships between variables and understanding the determinants of wages.  
2. **Predictive performance:** selecting the model that best predicts hourly wages, even if it requires greater complexity or reduces interpretability.  

---

## Objectives
- Build simple and multiple linear regression models to study hourly wages.  
- Analyze the trade-off between **interpretable models** (parsimonious, with clear coefficients) and **predictive models** (better fit, but less interpretable).  
- Assess the **statistical significance** of predictors.  
- Apply **robust regression models** to mitigate the impact of outliers.  
- Address the **assignments proposed in the course guidelines**, documenting the full modeling process.  

---

## Tools
- **Language:** R  
- **Main libraries:**  
  - `tidyverse`  
  - `tidymodels`  
  - `robustbase`  

---

## Project Structure
The project follows the **structure defined in the course guidelines**, including:  
- Data preprocessing and exploratory analysis.  
- Modeling with simple and multiple linear regressions, quadratic terms, and interactions.  
- Estimation of robust models in the presence of outliers.  
- Comparison between interpretable models and models with higher predictive power.  

---

## Results and Conclusions
- Significant gender differences were found in the effect of education on wages.  
- Potential experience shows a non-linear effect (increasing returns at first, but diminishing at higher levels).  
- Robust models proved useful to validate the stability of the results when outliers are present.  
- The choice of the “best model” depends on the goal: **explain relationships** or **maximize predictive accuracy**.  

---

## Relevance
This project illustrates the **practical application of regression models in R**, integrating:  
- Descriptive and exploratory analysis.  
- Model building and diagnostic checking.  
- Robust regression approaches to handle outliers.  
- Critical discussion of the balance between **explainability** and **predictive performance**.  

Thus, it combines both statistical rigor and applied orientation, showing how different modeling strategies can address distinct analytical goals.  

---