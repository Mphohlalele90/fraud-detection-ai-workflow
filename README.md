# Fraud Detection AI Workflow

This repository contains the project work for the **AI Development Workflow** assignment in the PLP Academy course *AI for Software Engineering*.

---

## Project Overview

This project demonstrates the end-to-end AI development workflow using two realistic case studies:

1. **Fraud Detection in Loan Applications**  
   - Real-time classification of potentially fraudulent loan applications for banks.
   - Covers data preprocessing, model training (Random Forest), evaluation, deployment planning, and ethical considerations.

2. **Hospital Readmission Risk Prediction**  
   - Predicts 30-day readmission risk for discharged patients at Chris Hani Baragwanath Hospital (Bara), South Africa.
   - Focuses on data strategy, bias and privacy, modeling approaches, and deployment in a healthcare context.

Both use cases emphasize the importance of ethical AI, bias mitigation, and practical deployment challenges.

---

## Repository Structure

All project files are in the root directory:

- `fraud_detection_workflow.ipynb` – Main notebook (contains both case studies, code, and analysis)
- `AI Development Workflow Assignment.pdf` – Assignment brief
- `README.md` – This file

> **Note:** There are no subfolders; mock data CSVs and images should be uploaded as prompted in the notebook.

---

## How to Use

### Option 1: Google Colab (Recommended)

1. Open the notebook in Google Colab:  
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Mphohlalele90/fraud-detection-ai-workflow/blob/main/fraud_detection_workflow.ipynb)
2. Upload the required mock data CSV when prompted.
3. Follow the notebook cells for a step-by-step AI workflow demonstration.

### Option 2: Run Locally

1. Clone this repository and ensure you have Python 3.x installed.
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn numpy ipython
   ```
3. Open the notebook with Jupyter or VSCode:
   ```bash
   jupyter notebook fraud_detection_workflow.ipynb
   ```
4. Upload the mock data CSV when prompted in the notebook.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## Ethics & Bias Considerations

- **Fraud Detection:** Addresses risks of unfairly flagging applicants from underrepresented locations. Strategies include using diverse datasets and fairness testing.
- **Hospital Readmission:** Discusses patient privacy (POPIA compliance), bias from healthcare access disparities, and the need for fairness-aware modeling.

---

## AI Development Workflow Diagram

The notebook includes a visual diagram of the AI workflow (CRISP-DM framework) and detailed markdown reflections on challenges, trade-offs, and improvements.

---

## Contact

Created by Mpho Hlalele
