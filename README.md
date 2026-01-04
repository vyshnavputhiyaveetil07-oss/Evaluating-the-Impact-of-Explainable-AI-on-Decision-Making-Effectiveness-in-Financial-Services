# Evaluating the Impact of Explainable AI (XAI) on Decision-Making Effectiveness in Financial Services

## Project Overview
This repository supports the MSc Business Analytics dissertation titled:

**“Evaluating the Impact of Explainable AI (XAI) on Decision-Making Effectiveness in Financial Services: A Cross-Industry Comparative Analysis.”**

The project examines how explainable artificial intelligence can support transparency, interpretation, and human oversight in financial decision-making. Rather than optimising predictive performance alone, the study focuses on how explainability enhances understanding and responsible use of machine learning outputs in high-stakes financial contexts.

---

## Repository Structure

xai-financial-decision-making/
│
├── data/
│ └── README_data_sources.md
│
├── notebooks/
│ └── xai-financial-analysis.ipynb
│
└── README.md

---

## Data Sources
This project uses **simulated financial data** generated within the Jupyter Notebook to reflect common financial decision variables such as income, loan amount, credit score, and age.

No real customer or proprietary data are used.  
This approach ensures reproducibility, ethical compliance, and alignment with academic research standards.

Details of data assumptions and variable definitions are provided in:
- `data/README_data_sources.md`

---

## Analytical Approach
- A **Random Forest classifier** is implemented as the primary predictive model.
- Model evaluation includes accuracy, precision, recall, F1-score, and ROC-AUC.
- Explainability is achieved through **intrinsic Random Forest feature importance**, highlighting the most influential variables driving predictions.
- The model is interpreted as a **decision-support tool**, not a fully automated decision-making system.

---

## How to Run the Code
1. Open the notebook:  
   `notebooks/xai-financial-analysis.ipynb`
2. Run all cells sequentially from top to bottom.
3. All data generation, model training, evaluation, and visualisations will be reproduced automatically.

---

## Explainability Method Used
- **Intrinsic Random Forest Feature Importance**

---

## Ethical Considerations
- All data are simulated and anonymised.
- No human participants or personal data are involved.
- Model outputs are intended to **support human judgement**, not replace professional decision-making.
- Results are interpreted with explicit acknowledgement of uncertainty and model limitations.

---

## Reproducibility
All analyses reported in the dissertation are fully reproducible using the provided Jupyter Notebook.  
The repository supports transparency and verification in line with best practices in business analytics research.

---

## Author
MSc Business Analytics  
University of Greenwich
