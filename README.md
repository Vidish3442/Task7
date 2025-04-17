# 📊 Sales Data Analysis using SQLite and Python

This project demonstrates how to perform basic **sales data analysis** using **SQLite** and **Python**. The objective is to extract key sales metrics like **total quantity sold** and **revenue per product**, and visualize the results using `matplotlib`.

---

## 📌 Project Goals

- Calculate **total quantity sold per product**
- Calculate **total revenue per product**
- Calculate **revenue share per product**
- Visualize results using bar and pie charts

---

## 🛠️ Tools & Libraries

- **Python**
  - `sqlite3` – Database operations
  - `pandas` – Data manipulation
  - `matplotlib` – Visualization
- **SQLite** – Lightweight embedded database

---

## ✨ Features

- Creates an SQLite database `sales_data.db`
- Creates a `Sales` table with `Product`, `Quantity`, and `Price`
- Inserts sample sales data (Laptop, Smartphone, Headphones, etc.)
- Performs SQL queries for:
  - Total quantity sold
  - Total revenue
  - Revenue share
- Saves charts:
  - `total_quantity_sold_by_product.png`
  - `revenue_by_product.png`
  - `revenue_share_by_product.png`

---

## 🚀 How to Run

### 1. Install Dependencies

```bash
pip install pandas matplotlib sqlite3
```
### 2. Run the Script 🏃‍♂️
**Open the `task7.ipynb`** file in Jupyter Notebook, JupyterLab, or VS Code to run the code.


- This will :
  - `Create sales_data.db if missing`
  - `Insert sample data`
  - `Calculate totals & shares via SQL`
  - `Save charts as:`
       - `total_quantity_sold_by_product.png`
       - `revenue_by_product.png`
       - `revenue_share_by_product.png`
### 3. View Results 👀
 Open the generated .png files in your project folder to see the visualized data.

## 📂 Folder Structure

```plaintext
📁 Task7
│
├── Task7.ipynb       # Python script
├── Screenshots       # images of Plots
├── sales_data.db     # SQLite database
└── README.md         # This file
