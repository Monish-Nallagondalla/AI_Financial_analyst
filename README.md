# AI Financial Analyst

AI Financial Analyst is a Python-based application that leverages artificial intelligence to provide comprehensive financial analysis, including stock recommendations and the latest company news. It integrates web search capabilities to ensure up-to-date information retrieval.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Running the Financial Analyst](#running-the-financial-analyst)
  - [Interactive Playground](#interactive-playground)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Financial Analysis**: Utilizes YFinanceTools to gather stock prices, analyst recommendations, stock fundamentals, and company news.
- **Web Search**: Employs DuckDuckGo for web searches, ensuring information is sourced and presented effectively.
- **Multi-Agent System**: Combines agents for finance and web search tasks to deliver comprehensive responses.

  ---

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Monish-Nallagondalla/AI_Financial_analyst.git
   cd AI_Financial_analyst
   ```

2. **Install Dependencies**

Install all required Python packages using pip:

```bash
pip install -r requirements.txt
```
3. **Set Up Environment Variables**

Create a .env file in the project root directory with your API keys:
```env
PHI_API_KEY=your_phi_api_key
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
```
Replace your_phi_api_key, your_groq_api_key, and your_openai_api_key with your actual API keys.

---

## Usage
Running the Financial Analyst
Use Financial_Analyst.py to execute tasks such as retrieving stock information, analyst recommendations, or company news. Modify the queries as needed in the script.
Example:
```python
multi_ai_agent.print_response(
    "Summarize analyst recommendations and share the latest news for NVDA",
    stream=True
)
```

---

## Interactive Playground
Launch the playground using playground.py:

```bash
python playground.py
```
1.Open the Phi Data Playground.

2.Select the endpoint option.

3.Set the endpoint to localhost:7777.

4.Use the interactive UI to test the agents.

---

## File Structure

- .env: Contains the API keys needed to access external services.
- requirements.txt: Lists the dependencies for the project.
- Financial_Analyst.py: Defines the main agents for web search and financial analysis.
- playground.py: Sets up a web-based playground for testing and interacting with the agents.

---

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgements

- [Phi Data](https://phi.com) - For providing advanced AI tools and services.
- [YFinance](https://pypi.org/project/yfinance/) - For the Python library to access financial data from Yahoo Finance.
- [DuckDuckGo](https://pypi.org/project/duckduckgo-search/) - For their search API to fetch web results.
- [Groq AI](https://groq.com) - For providing the Groq AI model that powers financial and web search agents.
- [OpenAI](https://openai.com) - For providing the GPT models that are utilized for natural language processing tasks.

---

## Caution
This project is for educational and demonstration purposes only. The information provided by the agents should not be used for making actual financial decisions. Always consult with a professional financial advisor before making any financial or investment decisions.
