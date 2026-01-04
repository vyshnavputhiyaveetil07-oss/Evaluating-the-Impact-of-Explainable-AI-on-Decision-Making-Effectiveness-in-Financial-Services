# Data Sources Documentation

This document describes the data used for the MSc Business Analytics dissertation:

**“Evaluating the Impact of Explainable AI (XAI) on Decision-Making Effectiveness in Financial Services: A Cross-Industry Comparative Analysis.”**

---

## Overview of Data Usage

This project uses **simulated financial data generated programmatically within the Jupyter Notebook**.  
No external datasets are directly loaded, downloaded, or processed as part of the analytical workflow.

The use of simulated data ensures:
- Full reproducibility of results
- Ethical and legal compliance
- Transparency in model development and evaluation
- Alignment with academic research standards

---

## Simulated Financial Dataset

The simulated dataset is designed to reflect common variables used in financial decision-making contexts, including:

- Income
- Loan amount
- Credit score
- Age
- Binary financial risk outcome (target variable)

These variables are generated using controlled random distributions to approximate realistic financial patterns while avoiding the use of real customer data.

All data generation steps are fully documented and executable within the notebook:
- `notebooks/xai-financial-analysis.ipynb`

---

## Purpose of Simulated Data

Simulated data is used to:
- Evaluate the behaviour of a Random Forest classifier in a financial decision context
- Examine how intrinsic explainability (feature importance) supports interpretation of model outputs
- Enable controlled experimentation without confidentiality or access constraints

This approach is commonly adopted in academic analytics research where access to real financial data is restricted.

---

## Ethical and Legal Compliance

- No real personal, customer, or proprietary data are used
- No Kaggle or restricted datasets are involved
- All data is generated solely for academic purposes
- The project complies with GDPR principles and university ethical guidelines
- Results are intended for educational evaluation of explainable AI, not operational deployment

---

## Reproducibility

Because the data is generated dynamically within the notebook, all analyses reported in the dissertation can be fully reproduced by executing the notebook from start to finish.

This supports transparency, verification, and methodological rigour.
 
