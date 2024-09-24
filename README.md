
# Stock Information Extractor & Analyzer

## Project Overview

This project is designed to extract stock information from websites, summarize the data, analyze the key financial metrics, and provide a final recommendation on whether to buy the stock or not. The project leverages multiple agents for research, financial analysis, and investment advice, along with task-based automation to streamline the process.

## Features

- **Data Extraction:** Gathers up-to-date stock information from relevant sources.
- **Summarization:** Compiles news articles, press releases, and industry reports into a concise summary.
- **Financial Analysis:** Analyzes key financial metrics, stock performance, and market trends.
- **Recommendation Engine:** Provides a detailed recommendation on whether to buy the stock, based on comprehensive research and analysis.
- **Task Automation:** Uses agents and tasks to handle various aspects of research, analysis, and reporting.

## Technologies Used

- **Python** for backend logic and automation.
- **CrewAI** for managing agents and tasks.
- **dotenv** for environment variable management.
- **Textwrap** for formatting output.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/stock-info-extractor.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd stock-info-extractor
   ```

3. **Install dependencies:**

   You can install the required dependencies by using pip:

   ```bash
   pip install crewai python-dotenv textwrap
   ```

4. **Configure environment variables:**

   Create a `.env` file in the root directory to store any necessary API keys or configuration values.

   Example:

   ```bash
   API_KEY=your_api_key_here
   ```

## How to Use

1. **Run the Application:**

   To start the stock analysis process:

   ```bash
   python main.py
   ```

2. **Input the company name:**

   When prompted, provide the name of the company you want to analyze.

   Example:

   ```bash
   What is the company you want to analyze?
   Apple
   ```

3. **View Results:**

   The program will extract, analyze, and summarize stock information, providing a comprehensive report with a final recommendation (Buy/Sell).

   Example output:

   ```bash
   ########################
   ## Here is the Report
   ########################
   Stock Recommendation: BUY
   Reason: Strong financials, positive market sentiment, and insider buying activity.
   ```
