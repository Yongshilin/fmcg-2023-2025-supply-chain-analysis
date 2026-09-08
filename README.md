# FMCG Supply Chain Profitability Analysis (2023-2025)

## Project Overview

This project analyzes profitability from a **supply chain perspective** for an FMCG company. The dataset is from Kaggle (https://www.kaggle.com/datasets/atharvasoundankar/fmcg-sales-marketing-and-profit-data), and the analysis is structured around supply chain decision-making — evaluating performance across regions, product categories, sales channels, promotions, and time trends to identify cost drivers and improvement opportunities.

**Dataset:** 18,240 order records (2023–2025) | 5 regions | 5 product categories | 4 sales channels

**Objective:** Diagnose supply chain profitability structure and quantify cost-saving opportunities.

**Key Result:** Identified **~$320K/year** in potential savings from two quantified opportunities. A third opportunity (promotion optimization) is identified for further testing.

**Deliverables:**
- Bilingual HTML reports (English & Chinese) — generated automatically upon running the analysis
- Five CSV files (region, category, channel, promotion, monthly trend) — for data and business teams

---

## Key Findings

| Opportunity | Current | Target | Savings/Year |
|-------------|---------|--------|--------------|
| Beverages COGS | 67.0% | 58.9% (category avg.) | ~$303K |
| Oceania Logistics | 8.0% | 7.0% (regional avg.) | ~$16K |
| **Total (Quantified)** | | | **~$320K** |

| Opportunity (To Be Tested) | Current | Benchmark |
|---------------------------|---------|-----------|
| Festival Promotion Discount | 16.6% | Loyalty Cashback 12.2% (198% ROI) |

### Best & Worst Performers

| Dimension | Best | Worst |
|-----------|------|-------|
| Region | Europe (23.6% margin) | Oceania (19.6% margin) |
| Category | Personal Care (28.1% margin) | Beverages (14.0% margin) |
| Channel | Wholesale (25.9% margin) | Online (12.4% margin) |
| Promotion | No Promo (317% ROI) | Festival Campaign (123% ROI) |

---

## Technical Stack

- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **Reporting:** HTML / CSS (self-contained reports)

---

## Reports
- **Click here to preview:** `https://yongshilin.github.io/fmcg-2023-2025-supply-chain-analysis/`

- Running the analysis notebook automatically generates two HTML reports:

`FMCG_supply_chain_report_EN.html` - Static HTML report (English) 
`FMCG_supply_chain_report_CN.html` - Static HTML report (Chinese) 

The reports will open automatically in your default browser upon generation (open the .py file or .ipynb file, then click 'run all').


---

## Repository Structure

```

├── SCM_Analysis_Full.ipynb
├── SCM_Analysis_Full.py  
├── report graphs/               # All charts
├── *.html                       # HTML reports (auto-generated)
├── *.csv                        # Analysis results by dimension
├── README.md

```


## How to Run

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook SCM Analysis Full.ipynb
```

Run all cells. The analysis will:

1. Process the data and analyze from 5 different dimensions (regions, product categories, sales channels, promotions, and time trends)
2. Generate all charts in report graphs/
3. Export CSV files
4. Create and automatically open two HTML reports (English & Chinese) in your browser
5. You can print PDF versions for the HTML reports (I attach PDFs here for better preview)

Author

[Yongshi Lin] — [LinkedIn: Yongshi Lin /Email:14yslin@gmail.com]
