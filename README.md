# Gold Price Prediction using Machine Learning

## 📌 Overview
This project uses a **Random Forest Regressor** to predict gold prices (GLD) by analyzing market indicators like the S&P 500, Silver prices, and Oil prices.

## 📊 Results
- **Model Accuracy:** 98.9% (R-Squared Score)
- **Key Discovery:** Silver (SLV) has the highest correlation (0.87) with Gold prices.

## ⚠️ 2026 Stress Test
I tested this model against live April 2026 data.
- **Actual:** $434.38 | **Predicted:** $167.27
- **Insight:** This project taught me about **Extrapolation Limits**. Tree-based models cannot predict values outside their training range, highlighting the need for LSTMs or updated datasets in a production environment.

## 🛠️ Tech Stack
Python, Pandas, Scikit-Learn, Seaborn, Matplotlib
