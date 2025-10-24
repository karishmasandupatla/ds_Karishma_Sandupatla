# Web3 Trading Data Science Assignment

## Candidate: **Karishma Sandupatla**

---

## 🔗 Colab Notebook

📘 [Open in Google Colab](https://colab.research.google.com/drive/1zTne4BTP-3-NzMSeTdIIsil98Vd2q6Vm#scrollTo=htN_SaT053uH)

---

## 🧭 Instructions to Run

1. **Open the above notebook in Google Colab.**

   Make sure the folder `csv_files/` contains:
   - `historical_data.csv` → Historical trader data  
   - `fear_greed_index.csv` → Bitcoin market sentiment data  
   (Rename if needed and update paths accordingly.)

2. **Run all cells sequentially:**
   - Data cleaning and preprocessing  
   - Aggregation of trader data by day  
   - Merging with the Fear & Greed dataset  
   - Exploratory Data Analysis (EDA)

3. **Outputs:**
   - All generated plots are saved in the `outputs/` folder.  
   - Aggregated and merged CSVs are saved in the `csv_files/` folder.

---

## 🧩 Notes

- **Numeric Mapping:**
  ```
  Extreme Fear = 0
  Fear = 1
  Neutral = 2
  Greed = 3
  Extreme Greed = 4
  ```
  Used for correlation and analysis.

- **Columns in `merged_data.csv`:**
  | Column | Description |
  |---------|-------------|
  | trade_date | Date of trade |
  | daily_pnl | Total profit/loss for that day |
  | daily_volume | Total trading volume in USD |
  | num_traders | Unique number of traders |
  | classification | Market sentiment (Fear/Greed) |
  | classification_num | Numeric mapping for sentiment |

- **Purpose:**  
  To analyze how trader behavior (PnL, volume, activity) aligns with overall **market sentiment**, uncovering behavioral and profitability patterns.

---

## 📊 Folder Structure

```
ds_k_s/
├── notebook_1.ipynb              # Main Colab notebook
├── notebook_2.ipynb              # Optional additional analysis
├── csv_files/
│   ├── daily_trader_stats.csv    # Aggregated trader data
│   ├── merged_data.csv           # Merged with Fear & Greed dataset
├── outputs/
│   ├── pnl_vs_sentiment.png
│   ├── volume_vs_sentiment.png
│   ├── num_traders_vs_sentiment.png
│   ├── correlation_heatmap.png
├── ds_report.pdf                 # Final summarized report
└── README.md                     # This file
```

---

## 📩 Contact

For any queries, please reach out to:  
**Karishma Sandupatla**
