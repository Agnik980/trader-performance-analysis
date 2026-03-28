# Trader Performance Analysis

## Project Overview

This project analyzes the relationship between **trader performance** and **market sentiment (Fear & Greed Index)**.
The goal is to understand how market emotions influence trading outcomes and to derive actionable insights for better trading strategies.

---

## Objective

* Analyze how **market sentiment (Fear/Greed)** impacts trader profitability
* Identify patterns in trading behavior under different sentiment conditions
* Provide **data-driven strategy recommendations**

---

## Dataset

The project uses:

* Trader performance data (PnL, trade size, buy/sell activity)
* Market sentiment data (Fear & Greed Index)

---

## ⚙️ Methodology

### 1. Data Cleaning

* Removed missing/null values
* Standardized column formats

### 2. Feature Engineering

* Created new features:

  * **PnL_bin** (Profit/Loss classification)
  * **Normalized PnL**
  * **Buy Ratio**
  * **Average Trade Size**

### 3. Exploratory Data Analysis (EDA)

* Compared trader performance across sentiment categories
* Visualized trends using bar charts and line plots

### 4. Basic Predictive Modeling

* Built a **Logistic Regression model** to predict:

  * Whether a trade will be **profitable or not**
* Features used:

  * Sentiment
  * Trade size
  * Buy ratio

---

## Key Insights

* Traders tend to earn **higher profits during Greed phases**
* Losses are more frequent during **Fear phases**
* Trading behavior changes significantly with sentiment
* Risk-taking increases during high market optimism

---

## Strategy Recommendations

*  Avoid trading during **Extreme Fear** (high loss probability)
* Increase position size cautiously during **Greed phases**
* Use **market sentiment as an input feature** in trading strategies
* Apply **risk management (stop-loss)** during volatile periods

---

## Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn

---

## How to Run
1. Run the notebook:
 jupyter notebook


## Output

* Average Closed PnL by Classification
  ![Uploading image.png…]()
* Frequency distribution
  ![Uploading output.png…]()

* position size analysis
  ![Uploading pos.png…]()

* long short ratio classification
  ![Uploading longshort.png…]()

* leverage distribution
  ![Uploading leverage.png…]()

* Tred Frequency
  ![Uploading Tred Frequency.png…]()



---

##  Conclusion

Market sentiment plays a crucial role in trading performance.
By incorporating sentiment analysis into trading strategies, traders can make more informed decisions and improve profitability.

---

## Future Improvements

* Add advanced ML models (Random Forest, XGBoost)
* Build an interactive dashboard (Power BI / Streamlit)
* Perform time-series analysis

---



