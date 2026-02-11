# Clothing Retail Sales & Inventory Management System

## Project Overview
This project is a **Clothing Retail Sales & Inventory Management System** designed for back office operations. It helps track sales, revenue, stock levels, and profitability of items in a retail store. The project demonstrates the use of data analysis and visualization to support business decision-making.

---

## Features

- **Total Revenue & Total Units Sold:** Quick summary metrics.
- **Low Stock Alert:** Identifies items with low inventory.
- **Quantity Sold by Size:** Helps track which sizes are performing better.
- **Top 5 Items by Profit:** Highlights the most profitable products.
- **Revenue by Category:** Tracks revenue contributions across categories.
- **Top 5 Items by Revenue:** Identifies best-selling products.
- **Daily Revenue Trend:** Tracks sales over time to identify trends.

---

## Data Description

### 1. `Sales_entry.csv`
| Column         | Description                     |
|----------------|---------------------------------|
| Date           | Date of sale                    |
| Product ID     | Unique identifier for product   |
| Quantity Sold  | Number of units sold            |
| Selling Price  | Price per unit sold             |
| Total Amount   | Quantity Sold × Selling Price   |

### 2. `Product_data.csv`
| Column            | Description                                  |
|------------------|----------------------------------------------|
| Product ID        | Unique identifier for product                |
| Category          | Product category (Jeans, Kurti, Shirt, etc.)|
| Item Name         | Name of the product                          |
| Size              | Size of the product (S, M, L, XL)           |
| Color             | Color of the product                         |
| Cost Price        | Purchase price of the product                |
| Selling Price     | Selling price of the product                 |
| Profit            | Selling Price − Cost Price                   |
| Stock             | Current stock quantity                        |
| Low Stock Alert   | Threshold for low stock                      |
| Updated Stock     | Stock after sales                             |

---


---

## Instructions to Run

1. Clone this repository:
```bash
git clone https://github.com/yourusername/Clothing-Retail-Management.git
