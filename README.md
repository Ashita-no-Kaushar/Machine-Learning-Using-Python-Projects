# 🏭 Industry-Expert Machine Learning Projects

## 📖 Overview

This repository contains a portfolio of **Machine Learning projects** developed during an intensive **Industrial Skill Development Program** at college.

These projects were built under the direct mentorship of **visiting industry experts**, with the goal of bridging the gap between academic theory and real-world application by simulating actual **data science workflows** used in business environments.

***

## 📂 Project Portfolio

| #  | Project Name                 | Domain              | Key Algorithms                                   |
|----|-----------------------------|---------------------|--------------------------------------------------|
| 01 | **Concrete Strength Prediction** | Construction/Materials | Linear Regression, Random Forest, XGBoost        |
| 02 | **Real Estate Price Prediction** | Real Estate        | Linear Regression, VIF Feature Selection         |
| 03 | **Retail Price Optimization**    | Retail/Sales       | Decision Tree Regressor, Linear Regression       |

***

## 🛠 Project Details

### 1. Concrete Strength Prediction

- **Goal:** Predict the compressive strength of concrete based on its composite ingredients (cement, water, ash, etc.)
- **Context:** Concrete strength is highly non-linear and depends on complex chemical interactions, making it a challenging regression problem
- **Key Techniques:**
  - Rigorous **EDA** on ingredient distributions and relationships
  - **VIF (Variance Inflation Factor)** to handle multicollinearity among predictors
  - Benchmarked **Linear Regression** against **Random Forest** and **XGBoost**
- **Outcome:** Ensemble methods (especially **XGBoost**) achieved around **90% prediction accuracy**, significantly outperforming Linear Regression on non-linear material strengths

***

### 2. Real Estate Price Prediction

- **Goal:** Forecast **housing prices per unit area** using location and property characteristics
- **Context:** Real estate valuation requires identifying high-impact features (like location) and filtering out noise
- **Key Techniques:**
  - **Data cleaning**, including handling date fields and standardizing numerical inputs
  - **Linear Regression** chosen for interpretability to understand how each feature drives price
  - **Cross-Validation** to ensure generalization to unseen properties
- **Outcome:** Built a robust model highlighting **Distance to MRT** and **Number of Convenience Stores** as primary drivers of price

***

### 3. Retail Price Optimization

- **Goal:** Determine the **optimal unit price** for products to maximize sales or revenue
- **Context:** Retail pricing is often rule-based and influenced by competitors rather than simple linear trends
- **Key Techniques:**
  - **Decision Tree Regressor** to capture non-linear pricing rules and competitor signals (e.g., `comp_1`, `freight_price`)
  - **Feature importance analysis** to identify which factors most strongly influence the optimal price point
- **Outcome:** The Decision Tree Regressor reduced prediction error by **~15%**, successfully identifying non-linear **price thresholds** and **profitable segments**

***

## 💻 Tech Stack

- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn, XGBoost, Statsmodels
- **Statistical Analysis:** Variance Inflation Factor (VIF)

***

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/machine-learning-python-projects.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd machine-learning-python-projects
   ```

3. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost statsmodels
   ```

4. **Run a project (example – Concrete Model Predictions):**
   ```bash
   cd 01_concrete_model_predictions
   python concrete_strength_prediction.py
   ```

***

## 👨‍💻 Author & Acknowledgements

- **Author:** Kaushar Halani
- **Program:** College Industrial Skill Development Program
- **Mentorship:** Projects guided by **industry experts** to ensure alignment with current **market standards**

If you find this repository useful, feel free to **star ⭐ the repo** and share it with others interested in practical machine learning projects!
