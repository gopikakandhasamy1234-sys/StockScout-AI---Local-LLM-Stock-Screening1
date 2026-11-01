# StockScout AI

A local LLM agent that converts natural-language stock queries into structured screening criteria and ranks stocks using financial data.

## Problem
Stock screeners need manual filter settings (P/E, market cap, growth, etc.). StockScout AI lets a user type a query such as "[example query]" and applies the matching filters automatically.

## Method
1. **Query parsing:** A local LLM ([model name, e.g. Llama / Mistral via Ollama]) converts the query into structured criteria ([JSON / schema]).
2. **Data:** Financial data is pulled from [source, e.g. yfinance] for [number] stocks.
3. **Filtering and ranking:** Stocks are filtered and ranked using user-defined metrics ([list metrics]).
4. **Interface:** [CLI / Streamlit / other].

## Evaluation
- Tested on [number] sample queries.
- Parsing accuracy: [x/y queries produced correct criteria].
- Failure cases: [e.g. ambiguous queries, unsupported metrics].

(If you did no formal evaluation, write: "Evaluated manually on sample queries; formal benchmarking is future work.")

## Limitations
- Depends on the quality of the local LLM's parsing.
- Financial data may be delayed or incomplete.
- Not financial advice.

## Setup
```bash
git clone [your repo link]
cd stockscout-ai
pip install -r requirements.txt
python app.py
```

## Tech Stack
Python, [LLM runtime], [data library], [interface library]

## Future Work
- [e.g. more metrics, query validation, backtesting]

## Author
Gopika K, M.Sc. Data Science, Madras School of Economics
