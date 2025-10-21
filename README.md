# Quant Value Project (QVP)

**Academic Year:** 2025–2026  
**Project Duration:** September 2025 – December 2025

## Project Description

The **Quant Value Project (QVP)** is a quantitative research initiative exploring modern approaches to **algorithmic trading and financial modeling**.
Our focus this semester (so far) spans three complementary domains:

1. **Pairs Trading** – identifying statistically correlated equities and exploiting temporary deviations using cointegration and z-score thresholds.
2. **Market Sentiment Embeddings** – constructing vectorized sentiment representations from financial news and company filings using transformer-based NLP models such as finBERT.
3. **Options Pricing** – implementing the **Black-Scholes model** for American-style contracts.

## Lead Contact Information

**Project Lead:** Severin Spagnola 
📧 Email: [severin.spagnola@sjsu.edu]  
💼 LinkedIn: [N/A]  
🏫 University: San José State University  

**Club Advisor:** Aditya

## Contributors

| Name | Role | Email | GitHub |
|------|------|--------|--------|
| Severin Spagnola | Project Lead | [severin.spagnola@sjsu.edu] | [@severin-spagnola](https://github.com/severin-spagnola) |
| [Name] | ABC XYZ | [email] | [@github](https://github.com/) |
| [Name] | ABC XYZ | [email] | [@github](https://github.com/) |

_(See `docs/members.csv` for full roster once added.)_

## Repository Structure

project-fa25-qvp/
├─ README.md
├─ environment.yml # TBA, environment setup (Python, dependencies)
├─ data/ # TBA, price data, sentiment feeds, options data
├─ notebooks/ # Notebooks for each sub-project
│ ├─ pairs_trading.ipynb
│ ├─ sentiment_embeddings.ipynb
│ └─ black_scholes_pricing.ipynb
├─ src/
│ ├─ pairs/ # cointegration testing, z-score trading logic
│ ├─ sentiment/ # text embedding & sentiment models
│ ├─ options/ # pricing functions, greeks, implied vol scripts
│ └─ utils/ # shared data loaders, visualization, config
├─ results/ # performance metrics & plots
└─ docs/
├─ members.csv
├─ info.json
└─ pitch_slides.pdf


## Project Goals

- Develop statistically robust pair-trading algorithms using correlation and cointegration tests 
- Build sentiment embeddings to quantify market sentiment, based off media sentiment as well as quarterly/yearly SEC filings, and integrate them into trading signals
- Implement and validate a Black-Scholes option pricing model for American-style options contracts
- Combine results into an interpretable framework for backtesting as well as potential alpha generation via live trading