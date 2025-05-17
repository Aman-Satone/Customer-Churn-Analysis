
# 📊 Customer Churn Analysis (EDA in Python)

## 🔍 Overview

This project focuses on **Exploratory Data Analysis (EDA)** to understand the key drivers of customer churn for a telecom company. Using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**, the goal is to uncover actionable insights to improve customer retention.

---

## 🎯 Objective

Identify the most influential factors contributing to customer churn to help stakeholders make data-driven decisions that reduce churn and enhance customer loyalty.

---

## 🧾 Dataset

- **Source**: Provided telecom customer data (`Customer Churn.csv`)
- **Rows**: ~7,000 customer records  
- **Columns**: Customer demographics, service usage, contract details, billing information, and churn status.

---

## 🔧 Tools & Technologies

- **Language**: Python  
- **Libraries**:  
  - `Pandas` for data manipulation  
  - `Matplotlib` and `Seaborn` for data visualization  
  - `NumPy` for numerical operations  
  - `Jupyter Notebook` for development  
- **File Used**: `CCA.ipynb` – Exploratory Data Analysis notebook

---

## 📈 Key Insights

- **Contract Type**:  
  - Month-to-month contracts have a **42% churn rate**.  
  - One-year and two-year contracts drastically reduce churn to **11%** and **3%**, respectively.

- **Payment Method**:  
  - **Electronic check** users show the highest churn (**45%**).  
  - Credit card and bank transfer users churn at **15–18%**.

- **Tenure**:  
  - Customers in their **first year** have a **50%** churn rate.  
  - This drops to **15%** after **three years**.

- **Internet Service**:  
  - **Fiber optic** users churn more than **DSL** users (30% vs 20%).

- **Senior Citizens**:  
  - Churn rate is **41%** for seniors, compared to **26%** for others.

---

## 📊 Visualizations

- Churn distribution by contract type, payment method, and tenure.
- Line graphs and bar plots to illustrate trends and comparisons.

---

## ✅ Recommendations

- Promote **long-term contracts** with incentives.
- Transition users away from **electronic checks**.
- Focus on **early-stage engagement**, especially in the first year.
- Develop **senior-focused retention programs**.

---

## 📁 Repository Structure

```
📦Customer-Churn-EDA/
 ┣ 📊 CCA.ipynb            # Main Jupyter Notebook with EDA
 ┣ 📂 data/
 ┃ ┗ 📄 Customer Churn.csv  # Dataset used
 ┣ 📄 README.md             # Project documentation
 ┗ 📄 Customer Churn Analysis.pdf  # Summary of findings
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Churn-EDA.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook CCA.ipynb
   ```

---

## 📬 Contact

For any questions or collaborations:  
**Your Name**  
[LinkedIn](https://www.linkedin.com/in/yourprofile) | [Email](mailto:your.email@example.com)
