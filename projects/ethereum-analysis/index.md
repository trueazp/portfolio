# Ethereum Market Trend & Volatility Analysis

## 1. Context

Cryptocurrency markets are characterized by high volatility and rapid price fluctuations. Ethereum, as one of the largest digital assets by market capitalization, has experienced multiple bull and bear cycles over the past decade.

Understanding long-term trend behavior and volatility dynamics is essential to support data-driven decision making in high-risk financial environments.

---

## 2. Problem Statement

How can historical Ethereum price data be analyzed to:

1. Identify long-term market trends  
2. Detect high-volatility periods  
3. Generate structured insights to support informed decision making  

---

## 3. Dataset

- **Source:** Yahoo Finance  
- **Period:** 2014 – 2024  
- **Granularity:** Daily data  
- **Variables:** Open, High, Low, Close, Volume  

The dataset represents structured time-series financial data suitable for trend and volatility analysis.

---

## 4. Data Preparation

Data preprocessing steps included:

- Handling missing values  
- Feature selection (focus on closing price & volume)  
- Data normalization for time-series modeling  
- Time-based segmentation for training and testing  

These steps ensured clean and structured input for both exploratory analysis and modeling.

---

## 5. Exploratory Data Analysis (EDA)

### Long-Term Price Trend 
![Price Trend](../../assets/img/ethereum/Ethereum_Historical_Price_Trend_Chart_Full.png)

Key observations:

- Clear multi-cycle growth pattern  
- Significant bullish periods followed by sharp corrections  
- Increasing market amplitude over time  

---

### Volatility Analysis

![Volatility Analysis](../../assets/img/ethereum/Ethereum_Trading_Volume_Chart_Full.png)

Key observations:

- High-volatility spikes align with major market transitions  
- Volatility clusters during bull-to-bear reversals  
- Market instability increases during rapid price expansions  

---

## 6. Modeling Approach

To explore predictive behavior, a Long Short-Term Memory (LSTM) model was implemented to capture temporal dependencies in time-series data.

Steps included:

- Data windowing for sequential learning  
- Model training using historical price sequences  
- Performance evaluation using RMSE  

The model was deployed using Streamlit for interactive visualization and real-time prediction simulation.

---

## 7. Key Insights

1. Ethereum exhibits cyclical growth patterns with recurring volatility clusters.  
2. Volatility spikes often precede major trend reversals.  
3. Long-term growth is accompanied by increasing risk amplitude.  
4. Time-series modeling can capture short-term momentum patterns but remains sensitive to market shocks.  

---

## 8. Business Implications

From a data analysis perspective:

- Volatility monitoring is critical for risk-aware decision making.  
- Identifying cycle transitions can improve timing strategies.  
- Structured historical analysis helps reduce emotionally driven decisions.  

Although cryptocurrency markets are inherently uncertain, analytical frameworks improve situational awareness.

---

## 9. Recommendation

Based on the analysis:

- Implement continuous volatility tracking as a risk signal  
- Combine trend analysis with volume behavior monitoring  
- Avoid relying solely on predictive modeling without contextual market analysis  
- Use structured historical insights to support informed decision making  

---

## 10. Deployment Preview

![Streamlit App Preview](../../assets/img/ethereum/Halaman_Utama.png)

The trained model was deployed using Streamlit to provide:

- Historical price visualization  
- Model prediction output  
- Interactive user interface for exploration  

(Note: Live deployment is currently inactive.)

---

## Tools Used

- Python (Pandas, NumPy, Matplotlib)  
- TensorFlow / Keras (LSTM)  
- Streamlit  
- Git & GitHub  

---
