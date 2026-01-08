# 🏥 Health Insurance Cross-Sell Prediction
**Capstone Project - AI/ML Post Graduate Diploma**

## 📌 Project Overview
This project builds a Machine Learning model to predict which Health Insurance customers are interested in purchasing Vehicle Insurance. By targeting the top 20% of likely buyers, the proposed solution aims to reduce cold-call volume by 80% while maintaining revenue.

## 📂 Repository Structure
- **`notebooks/`**: Jupyter Notebooks with full EDA, Training, and Evaluation.
- **`src/`**: Python scripts for modular execution.
- **`models/`**: Saved model artifacts (LightGBM).
- **`data/`**: Dataset files (or links to source).
- **`presentation/`**: Project slides (Technical & Business decks).

## 🛠️ Tech Stack
- **Language**: Python 3.10+
- **Libraries**: Pandas, Scikit-Learn, LightGBM, XGBoost, SHAP, Matplotlib/Seaborn.
- **Environment**: Google Colab / Jupyter.

## 📊 Key Results
- **Best Model**: LightGBM
- **Metric**: ROC-AUC Score of **0.851**
- **Fairness**: The model was audited for Gender Bias and found to have equal Recall rates for Male and Female customers.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt` (if applicable).
3. Run the notebook in `notebooks/Enzo_Limpo_CAPSTONE_AIML.ipynb`.

## 🤖 Generative AI Disclosure
Generative AI (Gemini) was used in this project for:
1. Debugging and optimizing the LightGBM/XGBoost training loops.
2. Structuring the repository and generating documentation.
3. Drafting the initial outline for the business presentation.
