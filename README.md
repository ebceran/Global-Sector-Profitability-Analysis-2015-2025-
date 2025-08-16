# 📊 Global Sector Profitability Analysis (2015–2025)

This project analyzes the **profitability and growth trends** of three key sectors by comparing:

* **Microsoft (Technology)**
* **Marks & Spencer (Retail)**
* **BP (Energy)**

---

## Key Metrics

The dataset (2015–2025) covers:

* **Gross Profit Margin (GPM)**
* **Net Profit Margin (NPM)**
* **Revenue Growth (YoY %)**
* **Net Profit Growth (YoY %)**

---

## Visualizations

The analysis was performed in **Python (Pandas + Matplotlib)** with supporting **Excel tables**.

Generated graphs include:

1. Gross Profit Margin Trends
2. Net Profit Margin Trends
3. Revenue Growth (YoY)
4. Net Profit Growth (YoY)

Each chart is annotated with brief insights (e.g., *“M\&S net profit margin proved more resilient than Debenhams in downturns”*).

<img width="1206" height="760" alt="Screenshot 2025-08-16 210738" src="https://github.com/user-attachments/assets/6a7f0042-0dac-452b-a5a6-c189b02b96b1" />
<img width="1256" height="773" alt="Screenshot 2025-08-16 210757" src="https://github.com/user-attachments/assets/da22481e-ac17-4228-b210-71a2485911e3" />

---

## Insights

* **Tech (Microsoft)** → consistently high margins and strong growth.
* **Retail (M\&S)** → volatile margins, vulnerable to structural challenges.
* **Energy (BP)** → stable but low-margin, sensitive to external cycles.

---

## Repository Structure

```
data/
 └── sector_profitability.csv   # Dataset (2015–2025)
figures/
 ├── gpm.png
 ├── npm.png
 ├── revenue_yoy.png
 └── netprofit_yoy.png
notebooks/
 └── data_sector_profitability.ipynb   # Python analysis
```

---

##  How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/global-sector-profitability.git
   cd global-sector-profitability
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/data_sector_profitability.ipynb
   ```

---

## ✨ Author

**Emine Ceran** – Financial Data Scientist in training, combining finance expertise with data-driven insights.

