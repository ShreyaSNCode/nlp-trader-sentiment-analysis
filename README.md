🚀 End-to-end data science project combining trading data with market sentiment to derive actionable insights.

Key finding: Trader performance is driven more by risk management than sentiment alone.

# 📈 NLP-Based Financial Sentiment Analysis for Market Insights

----

## 📌 Problem Statement

Financial markets are heavily influenced by public sentiment from news and social media. 
Understanding whether sentiment is bullish, bearish, or neutral can help traders and analysts make better decisions.

This project aims to analyze textual data and classify sentiment to uncover market trends.

---

## 📌 Objective
Analyze how market sentiment (Fear/Greed) influences trader behavior, risk-taking, and profitability.

---

## 💼 Business Use Case

- Helps investors understand market mood  
- Supports data-driven trading decisions  
- Identifies sentiment trends from financial text data

---

## 📂 Dataset Sources

- Historical Trader Data (Hyperliquid): [https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view]
- Bitcoin Market Sentiment (Fear/Greed Index): [https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view]

Note: Datasets are provided via external links due to size constraints.
---

## ⚙️ Methodology

- Data cleaning and preprocessing  
- Timestamp conversion and alignment  
- Merging datasets on date  
- Feature engineering (PnL, trade size, win rate)  
- Behavioral and performance analysis  
- Visualization and insights  
- Predictive modeling (bonus)  

---

## 📊 Key Insights

- Traders take **larger positions during Fear**, but profitability is lower → inefficient risk-taking  
- **Extreme Greed shows highest profitability**, indicating strong market conditions  
- Trade size has a **greater impact on profitability than sentiment alone**  

---

## ⚙️ Approach

1. Data Collection (news/social media)
2. Data Cleaning (remove noise, stopwords)
3. Text Preprocessing (tokenization, normalization)
4. Feature Extraction (TF-IDF / Bag of Words)
5. Model Training (Logistic Regression, Naive Bayes)
6. Evaluation (Accuracy, Precision, Recall)

----

## 🚀 Strategy Recommendations

- Reduce position sizes during Fear periods to avoid emotional trading  
- Increase participation during Extreme Greed phases  
- Focus on disciplined execution rather than increasing exposure  

---

## 📊 Key Insights

- Traders take higher risks during Fear but achieve lower returns  
- Extreme Greed phases show highest profitability  
- Trade size influences profitability more than sentiment

  
## 🤖 Bonus: Predictive Model

- Built a Random Forest model to predict trade profitability  
- Achieved ~63% accuracy after removing data leakage  
- Found that **trade size dominates prediction over sentiment**

---

## 📊 Sample Visualizations

![PnL Distribution](pnl_distribution.png)
![Trade Size](trade_size.png)

## ▶️ How to Run

1. Download notebook  
2. Install requirements:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn


