# ☕ Coffee Sales Analysis

Welcome to the **Coffee Sales Analysis** repository! This project delves into coffee sales data spanning from **March 1, 2024**, to **July 31, 2024**, offering a comprehensive understanding of customer preferences, sales trends, and business insights. The analysis was performed using Python and visualized with tools like Matplotlib and Seaborn.

## 🔗 [Explore the Hosted EDA Report](https://garry864.github.io/Coffee_Sales_Analysis/#missing)

---

## 📖 Project Overview

This analysis aims to uncover actionable insights from coffee sales data to guide business decisions. Key areas of focus include:

- **Transaction Details**: Date, time, coffee type, and price.
- **Payment Methods**: Card or cash transactions, with anonymized identifiers.
- **Customer Preferences**: Favorite coffee types and peak purchasing behaviors.

---

## ✨ Key Findings

### 1️⃣ **Overall Sales Trends**
- Sales started declining in **June**, despite steady performance earlier.
- **Peak Sales Hour**: Morning **10:00 AM**, with consistent sales between **12:00 PM and 6:00 PM**.
- **Best Day**: **Tuesday**, while **Monday** recorded the least sales.

### 2️⃣ **Top-Selling Coffee Types**
- **Americano with Milk** (23.65%) and **Latte** (21.45%) lead in sales.
- **Cappuccino** sales showed fluctuations but overall growth.
- **Espresso** and **Cocoa** are the least popular options.

### 3️⃣ **Insights by Coffee Type**
- **Latte**: Sales peaked at 10:00 AM.
- **Cappuccino**: Preferred in the evening.
- **Cortado**: Maintains steady noon sales.
- **Espresso**: Consistent across hours.

### 4️⃣ **Payment Trends**
- **Cards** dominate payment methods.
- **ANON cards** are the most frequently used anonymized identifiers.

### 5️⃣ **Time Series Forecasting**
- Conducted with ARIMA models.
- Parameters like **(1, 1, 13)** yielded optimal performance.
- Seasonal trends revealed sales declines post-June.

---

## 🛠️ Tools and Technologies

- **Python**: pandas, NumPy, Matplotlib, Seaborn, statsmodels, and scikit-learn.
- **EDA**: Bar charts, line plots, and histograms to identify key patterns.
- **Forecasting**: ARIMA modelling for sales predictions.

---

## 📂 Repository Contents

```plaintext
Coffee_Sales_Analysis/
├── data/
│   └── coffee_sales_data.csv      # Sales dataset (replace with the actual filename)
├── src/
│   ├── EDA_Report.ipynb                     # Exploratory Data Analysis script
│   ├── Coffee_Sales_Analysis.ipynb    # Time Series Analysis and Forecasting
├── Coffe_Sales_UM_Report.pdf      # Original analysis report
└── README.md                      # Project documentation

```
## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/garry864/Coffee_Sales_Analysis.git
cd Coffee_Sales_Analysis
```

### 2️⃣ Install Required Libraries
Ensure you have Python installed. Use the following command to install dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Explore the Analysis
- Run the scripts in the `/src/` folder to reproduce or extend the analysis.
- Open the **hosted EDA report** directly [here](https://garry864.github.io/Coffee_Sales_Analysis/#missing) or the HTML file in the `/Report/` folder.

---

## 🌟 Future Exploration Ideas

- **Customer Segmentation**: Identify customer groups for targeted campaigns.
- **External Factors**: Analyze the influence of weather, events, or holidays.
- **Dynamic Pricing**: Assess price elasticity across products.
- **Promotion Impact**: Evaluate the success of past campaigns to optimize future strategies.
- **Inventory Management**: Use insights for better stock planning.

---

## 🤝 Contributions

We welcome contributions! Feel free to fork the repository, create pull requests, or share new ideas for analysis. Let’s make coffee insights richer! ☕

---

## 📧 Contact

For questions or collaboration opportunities, please reach out through the repository or [GitHub profile](https://github.com/garry864).

---

🎉 **Thank you for exploring! Let's brew some data insights!**

