# 📈 StockScout AI

**Local LLM-powered stock screening using natural language.**

StockScout AI lets you describe the stocks you're looking for in plain English. A locally running LLM agent converts your query into structured screening criteria, then filters and ranks stocks using real financial data. No cloud APIs and no data leaving your machine.

## ✨ Features

- 🗣️ **Natural-language queries**: e.g., *"Find large-cap tech stocks with P/E under 25 and revenue growth above 10%"*
- 🤖 **Local LLM agent**: runs fully offline for privacy and zero API cost
- 🧩 **Structured criteria extraction**: converts free text into machine-readable filters (JSON)
- 📊 **Financial data integration**: pulls fundamentals and market metrics automatically
- 🏆 **Automated filtering & ranking**: sorts results by user-defined metrics

## 🛠️ Tech Stack

- **Language:** Python
- **LLM:** Local model (e.g., Ollama / Llama / Mistral)
- **Data:** Financial data API (e.g., yfinance)
- **Libraries:** pandas, requests, etc.

## 🚀 How It Works

1. **User enters a query** in natural language
2. **LLM agent parses it** into structured screening criteria
3. **Financial data is fetched** for the stock universe
4. **Filters are applied** and stocks are ranked by chosen metrics
5. **Results are displayed** in a clean table

## 📦 Installation

```bash
git clone https://github.com/<your-username>/StockScout-AI.git
cd StockScout-AI
pip install -r requirements.txt
```

## ▶️ Usage

```bash
python main.py
```

Example query:
