# Stock Volatility & Trading Volume Predictor
A Streamlit-based web application that provides next-day predictions of both stock price volatility and trading volume using an advanced LSTM deep learning model. Designed for investors, traders, and market analysts, the app integrates technical, macroeconomic, and sentiment-based signals to deliver data-driven insights.
## About the Project
Modern financial markets are influenced by a multitude of factors—ranging from corporate fundamentals to breaking news headlines. Our app simplifies this complexity by offering:
- Predicted Next-Day Volatility
- Predicted Next-Day Trading Volume

Both are powered by an LSTM model trained on enriched datasets combining:
- Technical Indicators (e.g., ROE, Quick Ratio)
- Macroeconomic Signals
- Financial News Sentiment, extracted using FinBERT

## Key Features
- LSTM-Powered Forecasting: Sequence-based modeling for time-series financial data
- FinBERT Sentiment Integration: Captures market mood from financial news headlines
- Macroeconomic & Technical Inputs: From central bank rates to firm-level ratios
- Interactive Visualizations: Clean, user-friendly Streamlit interface
- One-Click Access: No setup needed—just launch the app and explore predictions instantly

## Built With
- <img src="https://img.shields.io/badge/Streamlit-E14C4C?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
- <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
- <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
- <img src="https://img.shields.io/badge/FinBERT-Transformers-blueviolet?style=for-the-badge&logo=amazon&logoColor=white" alt="FinBERT">
- <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
- <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
- <img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
- <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly">

## How to Use
No installation needed — simply click the hosted link to launch the app.
> If you’re running locally:
1. Clone this repo
2. Install dependencies:
   
<pre> ```bash pip install -r requirements.txt ``` </pre>

3. Run

<pre> ```bash streamlit run app.py ``` </pre>

## Target Audience
This app is perfect for:
- Retail & institutional investors
- Traders seeking edge from volume/volatility insights
- Financial news readers looking to link headlines to market dynamics
- Stock analysts enhancing their forecasting toolkit

## Future Plans
① Model explainability with SHAP

② Portfolio-level prediction integration

③ News source customization and filtering

④ Integration with other real-time APIs for more data sources

## Contact
For questions or collaboration requests, please contact [us] at [eveme@bu.edu] / [yy3216@bu.edu] / [dizhaozh@bu.edu].

## Contributors: 
Dizhao Zhang, Yixi Yu, Shuomeng Guan
