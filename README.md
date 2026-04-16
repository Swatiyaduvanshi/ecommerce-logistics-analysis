# 🚚 E-Commerce Logistics & Order Analysis

A comprehensive data analysis project on a real-world Brazilian e-commerce dataset (89,316 orders) using Python, Pandas, Matplotlib, and Seaborn.

---

## 📊 Key Insights

| Metric | Finding |
|--------|---------|
| ✅ Fulfillment Rate | 97.9% of orders delivered successfully |
| ⏱️ Avg Delivery Time | ~12 days (estimated: ~23 days) |
| 🗺️ Top Customer State | São Paulo (42% of all customers) |
| 💳 Top Payment Method | Credit Card (73.6% of transactions) |
| 📦 Shipping Cost | ~20% of product revenue |
| 📈 Trend | Consistent YoY growth in order volume |

---

## 📁 Dataset Structure

```
Ecommerce Order Dataset/
├── train/
│   ├── df_Orders.csv        ← Order status & timestamps
│   ├── df_OrderItems.csv    ← Products, prices, shipping charges
│   ├── df_Customers.csv     ← Customer location data
│   ├── df_Payments.csv      ← Payment methods & values
│   └── df_Products.csv      ← Product categories & dimensions
└── test/
    └── (same structure)
```

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Notebook:** Jupyter Notebook (`.ipynb`)
- **Dataset Source:** [Kaggle – E-Commerce Shipping Dataset](https://www.kaggle.com/datasets/prachi13/customer-logistics-data)

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/ecommerce-logistics-analysis.git
   cd ecommerce-logistics-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Place the dataset** inside the project folder:
   ```
   Ecommerce Order Dataset/
       train/
           df_Orders.csv
           df_OrderItems.csv
           ...
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook ecommerce_logistics_analysis.ipynb
   ```

5. **Run All Cells** → `Kernel > Restart & Run All`

---

## 📈 Visualizations Generated

1. `order_status.png` — Order status bar + pie chart
2. `delivery_time.png` — Actual vs estimated delivery distributions
3. `monthly_trends.png` — Order volume over time
4. `customer_states.png` — Top 10 states by customer count
5. `payment_analysis.png` — Payment method usage & avg order value
6. `product_categories.png` — Top categories by revenue & avg price
7. `price_vs_shipping.png` — Scatter plot of price vs shipping cost
8. `late_delivery_heatmap.png` — Late delivery rate by month/year

---

## 💡 Business Recommendations

1. **Expand geographically** — 42% concentration in São Paulo; target underserved northern/western states
2. **Optimize last-mile delivery** — Shipping costs are ~20% of revenue; route optimization can reduce this
3. **Seasonal preparedness** — Late delivery spikes in certain months need proactive logistics planning
4. **Credit card loyalty program** — 73.6% use credit cards; EMI offers and cashback can increase CLV
5. **Premium category focus** — Some categories have high avg price but low volume; targeted marketing opportunity

---

## 📂 Project Structure

```
ecommerce-logistics-analysis/
├── ecommerce_logistics_analysis.ipynb   ← Main analysis notebook
├── README.md                            ← This file
├── requirements.txt                     ← Python dependencies
└── Ecommerce Order Dataset/             ← Dataset folder
    └── train/
```

---

*Made with ❤️ using Python & Jupyter | Dataset from Kaggle*
