# 📊 Crypto Market Sentiment Analysis & Trading Behavior

Analyzing how market sentiment (Fear vs Greed) influences trader behavior and profitability

---

##  Problem Statement

Financial markets are heavily influenced by investor sentiment.
This project explores how the **Fear & Greed Index** impacts:

* Trader behavior (volume, leverage)
* Profitability (PnL trends)
* Market decision patterns

The goal is to uncover whether sentiment can be used as a **predictive or contrarian trading signal**.

---

##  Dataset

* Historical trading data
* Fear & Greed Index data

These datasets were combined to analyze behavioral and performance patterns across different market sentiments.

---

##  Approach

###  Data Preprocessing

* Merged trading data with sentiment index
* Handled missing values and inconsistencies
* Standardized time-based records

###  Exploratory Data Analysis (EDA)

* Distribution of trades across sentiment phases
* Volume & leverage trends
* PnL variation across market conditions

###  Behavioral Analysis

* Compared trader activity during:

  * Fear phases
  * Neutral phases
  * Greed phases

###  Insight Extraction

* Identified patterns linking sentiment to trading outcomes
* Evaluated potential predictive signals

---

## Key Insights

* **Higher risk-taking during greed phases**
  → Increased leverage & trading volume

* **Profitability drops despite aggressive trading**
  → Suggests overconfidence in bullish markets

* **Fear phases show conservative behavior**
  → Lower risk, but more stable outcomes

* **Extreme greed often precedes negative PnL**
  → Indicates a strong **contrarian signal opportunity**

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Google Colab

---

##  Project Structure

```bash id="z8htm4"
├── notebooks/           # Jupyter notebooks (analysis)
├── data/                # Input datasets
├── outputs/             # Generated results & visualizations
├── csv_files/           # Processed datasets
└── README.md            # Documentation
```

---

##  How to Run

1. Open Google Colab
2. Upload the notebook (`notebook_1.ipynb`)
3. Upload required datasets:

   * `historical_data.csv`
   * `fear_greed_index.csv`
4. Run all cells

Outputs will be generated in:

* `csv_files/`
* `outputs/`

---

##  Future Improvements

*  Build predictive model using sentiment as feature
*  Apply machine learning for PnL forecasting
*  Backtest trading strategies based on sentiment signals
*  Deploy as an interactive dashboard (Streamlit)

---

##  Project Value

This project demonstrates:

* Real-world data analysis
* Behavioral insight extraction
* Financial data interpretation
* Ability to connect data → strategy

---

##  Contact

* 📧 [snehasingh2404@gmail.com](mailto:snehasingh2404@gmail.com)

---

⭐ If you found this project interesting, consider giving it a star!
