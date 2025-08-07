# 📊 Responsible Data Science Audit:
## Evaluating Fairness and Causal Impact in Kaggle’s Elo Recommendation Model

This project audits a solution to the [ELO Merchant Category Recommendation](https://www.kaggle.com/competitions/elo-merchant-category-recommendation) competition on Kaggle.  
We specifically focus on the notebook ["Elo World"](https://www.kaggle.com/code/fabiendaniel/elo-world) by Fabien Daniel (Kaggle user: `fabiendaniel`), a high-performing approach using credit card transaction history and merchant features to predict loyalty scores.

---

### Project Goals

- Evaluate model **accuracy**, **stability**, and **fairness** across subpopulations.
- Apply **causal inference techniques** (e.g., pre-post analysis, control-treatment comparison) to assess promotional targeting impact.
- Interpret model behavior using **SHAP** and **LIME** for global and local explanations.
- Propose improvements to data collection, preprocessing, and feature engineering for responsible deployment.

---

### Project Files

| File | Description |
|------|-------------|
| `Elo_Model_Audit_Causal_Fairness_ConnyFan.pdf` | Full audit report (10 pages) with findings, charts, and recommendations |
| `project_Final_Code.ipynb` | Main Kaggle notebook (audited code, modified and annotated) |
| `data/` | Sample transaction datasets (subset for demonstration) |

---

### Author

**Conny Fan**  
*Data Science & Mathematics, NYU*  
[LinkedIn](http://www.linkedin.com/in/jialaifan0625/) | jf4644@nyu.edu

---

### Acknowledgements

- Kaggle competition hosted by Elo
- Original notebook by [Fabien Daniel](https://www.kaggle.com/fabiendaniel)
