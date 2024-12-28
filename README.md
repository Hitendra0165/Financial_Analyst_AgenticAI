# Financial_Analyst_AgenticAi

This repository provides a Python-based framework for developing AI agents capable of performing financial analysis and web searches. The project integrates advanced AI models with external tools for retrieving financial data, conducting web searches, and summarizing information.

## Features

- **Finance AI Agent**: Uses YFinance tools to retrieve stock prices, analyst recommendations, company fundamentals, and news.
- **Web Search Agent**: Performs web searches using DuckDuckGo, ensuring that sources are always included.
- **Multi-Agent Collaboration**: Combines the Finance AI Agent and Web Search Agent to summarize data and present insights in a structured, markdown format.
- **Interactive Playground**: A web-based interface to interact with agents.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/financial-ai-agent-playground.git
   cd financial-ai-agent-playground

2. Create a virtual environment and activate it:
conda create -p Agent python==3.12
conda activate Agent/

3. Install the dependencies:
pip install -r requirements.txt

4. Create a .env file in the root directory and add the following keys:
PHI_API_KEY
GROQ_API_KEY
OPENAI_API_KEY

5. Usage
Financial_Agent.py
This script demonstrates how to set up and use multiple AI agents to perform tasks like financial analysis and web searches.

Run the script:
python financial_agent.py

Playground.py
The Playground.py script launches a web-based interface for interacting with the agents.

Run the playground:
python playground.py

## Key Dependencies

phidata
python-dotenv
yfinance
duckduckgo-search
fastapi
uvicorn
groq
openai

Contributing
Feel free to fork this repository, submit issues, or create pull requests to improve the project. Contributions are always welcome!

## Acknowledgments

Groq for providing cutting-edge AI models.
YFinance for financial data.
DuckDuckGo for search capabilities.
OpenAI for advanced natural language processing.


