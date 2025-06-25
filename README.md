# 🚗 Vehicle Insurance Analysis

This project presents a comprehensive **Exploratory Data Analysis (EDA)** on a real-world dataset consisting of over **381,000 vehicle insurance records**. The analysis was conducted to uncover key demographic and behavioral trends influencing a customer's likelihood to purchase or claim vehicle insurance.

---

## 📌 Project Objective

To identify significant features and customer behaviors that impact insurance claim interest. Insights derived from this analysis can be used to optimize marketing strategies, pricing models, and risk assessment frameworks within the insurance industry.

---

## 📊 Dataset Overview

The dataset includes:
- Demographics: `Gender`, `Age`, `Driving_License`, `Region_Code`
- Vehicle info: `Vehicle_Age`, `Vehicle_Damage`
- Policy data: `Annual_Premium`, `Policy_Sales_Channel`, `Vintage`
- Target variable: `Response` (0 = No Claim Interest, 1 = Interested)

---

## 🛠️ Technologies Used

- **Python**
  - `Pandas` – data manipulation and cleaning
  - `NumPy` – numerical computations
  - `Matplotlib` & `Seaborn` – data visualization
- Jupyter Notebook (for step-by-step analysis and visuals)

---

## 🔍 Key Insights

- **Age Group 25–50**: Most likely to respond positively to insurance offers.
- **Gender**: Males slightly more likely to show claim interest.
- **Vehicle Damage**: Strongest indicator of future claim interest.
- **Vehicle Age**: Newer vehicles are more frequently insured.
- **Region 28.0** and **Channel 152**: Show highest response rates.
- **Premium Outliers**: Removed for improved visualization and model accuracy.
- **Vintage (customer loyalty)**: Has minimal influence on claim behavior.

---

## 📈 Visualizations

- Boxplots for outlier detection
- Histograms and count plots for categorical & numerical distribution
- Feature-target analysis using grouped bar charts and heatmaps

---

## ✅ Conclusion

The project successfully demonstrates how **EDA can reveal actionable business intelligence** from raw insurance data. These insights lay the groundwork for building **predictive models** for customer segmentation, churn prediction, and fraud detection.

---

## 💡 Recommendations

- Target marketing towards **25–50 age group**.
- Develop renewal strategies for **damaged vehicle owners**.
- Incentivize insurance for **older vehicles**.
- Focus efforts on **high-performing sales channels and regions**.
