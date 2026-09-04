
# 📊 Sales Exploratory Data Analysis (EDA) Project

An end-to-end Exploratory Data Analysis (EDA) project built using Python, Pandas, Matplotlib, and Seaborn. This project analyzes customer purchasing patterns, payment preferences, and regional revenue trends from an e-commerce sales dataset.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Tech Stack & Tools](#-tech-stack--tools)
- [Dataset Structure](#-dataset-structure)
- [Key Steps & Analysis](#-key-steps--analysis)
- [Key Insights & Findings](#-key-insights--findings)
- [How to Run Locally](#-how-to-run-locally)
- [Project Structure](#-project-structure)

---

## 🚀 Project Overview
The primary goal of this project is to clean, process, and analyze sales transaction data to uncover actionable business insights. Using descriptive statistics and visual charts, this project addresses key questions such as:
- Which product categories generate the highest revenue?
- What are the most preferred payment methods among customers?
- How does sales performance vary across different regions?

---

## 🛠 Tech Stack & Tools
- **Language:** Python 3.x
- **Environment:** VS Code / Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn

---

## 📂 Dataset Overview
The dataset (`data.csv`) contains 1,000 sales records with the following key attributes:

| Column Name | Description |
| :--- | :--- |
| `Order_ID` | Unique transaction ID |
| `Date` | Date of purchase |
| `Customer_ID` | Unique customer identifier |
| `Gender` | Gender of the customer |
| `Age` | Age of the customer |
| `Region` | Geographic region (South, North, East, West, Central) |
| `Category` | Product category (Electronics, Clothing, Home, etc.) |
| `Product_Name` | Name of the specific item |
| `Quantity` | Quantity purchased |
| `Unit_Price` | Price per single unit (₹) |
| `Total_Sales` | Total revenue generated (`Quantity` × `Unit_Price`) |
| `Payment_Method` | Payment mode (UPI, Credit Card, COD, Net Banking) |
| `Customer_Rating`| Product rating (1.0 to 5.0) |
| `Returned` | Return status (Yes / No) |

---

## 🔍 Key Steps & Analysis

1. **Data Inspection:** Explored overall dimensions, data types, and descriptive statistics (`df.describe()`, `df.info()`).
2. **Data Cleaning:** Identified and handled missing values in `Age` and `Customer_Rating` columns using median/mean imputation methods.
3. **Outlier & Quality Detection:** Inspected distribution anomalies using Seaborn boxplots.
4. **Data Visualization:**
   - **Univariate Analysis:** Analyzed payment method distribution.
   - **Bivariate Analysis:** Measured sales revenue per category and region.
5. **Correlation Matrix:** Mapped numerical relationships using Seaborn heatmaps.

---

## 💡 Key Insights & Findings
- **Revenue Leaders:** **Electronics** and **Clothing** categories contribute the highest overall revenue.
- **Payment Trends:** Digital payments (**UPI** and **Credit Cards**) are the most frequently used transaction methods.
- **Geographic Insights:** The **South** and **North** regions account for the highest sales volume.

---

## ⚙️ How to Run Locally

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/sales-eda-project.git](https://github.com/your-username/sales-eda-project.git)
cd sales-eda-project
