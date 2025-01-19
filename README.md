# Multi-Agent Financial Analysis and Web Search Toolkit

This project implements a multi-agent AI system for financial analysis and web-based information retrieval. Powered by **Groq language models**, it integrates tools like **DuckDuckGo** and **YFinanceTools** to provide a robust and interactive platform for processing queries and generating insightful responses.

---

## Features

- **Web Search Agent**:
  - Searches the web using DuckDuckGo for real-time information.
  - Includes source attribution for credibility.

- **Financial AI Agent**:
  - Retrieves:
    - Stock prices
    - Analyst recommendations
    - Financial fundamentals
    - Company news
  - Displays results in tables for better clarity.

- **Interactive Playground**:
  - Provides a web-based interface for users to interact with agents seamlessly.
  - Supports multi-agent collaboration for complex queries.

---

## Requirements

- Python 3.8 or higher
- Required libraries: 
  - `openai`
  - `dotenv`
  - `phi`
  - `yfinance`
  - `duckduckgo_search`

Install dependencies:
```bash
pip install -r requirements.txt
Usage
Running the Financial Agent
To run the financial agent for specific queries:

bash
Copy
Edit
python financial_agent.py
Launching the Playground App
To start the interactive Playground:

bash
Copy
Edit
python playground.py
Access the app at http://localhost:8000.

Example Queries
Web Search:

"What are the latest developments in AI?"
Results include summarized insights with source links.
Financial Analysis:

"Summarize analyst recommendations and share the latest news for NVDA."
Fetches stock prices, news, and financial insights for NVIDIA.
Technologies Used
Groq Language Models: For natural language processing and tool integration.
DuckDuckGo: Web search engine for real-time information retrieval.
YFinanceTools: Access to stock market and financial data.
Playground: Interactive web app interface for agent collaboration.