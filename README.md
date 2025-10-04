# -Market-Research-Agent-Powered-by-Tavily-API
A Streamlit app that performs live market research using the Tavily API. It compares smartwatch competitors, extracts features, prices, and reviews, and visualizes insights using charts and graphs.

📘 Long Description (Final Polished Version)
📊 Market Research Agent — Powered by Tavily API

This Streamlit application performs real-time market research and competitor analysis using the Tavily Search API.
It collects live data about similar products, extracts their key features, price range, and customer sentiment,
and presents the results through clear and interactive charts and reports.

🚀 Key Features

Live Data Collection: Fetches real-time market information through Tavily API.

Competitor Discovery: Automatically identifies top competitors for any given product.

Feature Extraction: Summarizes unique selling points from product descriptions.

Price Estimation: Extracts PKR prices from search results and calculates an average.

Customer Insights: Collects and displays brief sentiment information.

Visual Analysis: Generates comparison charts using Matplotlib.

Secure Key Handling: Loads API key safely through a .env file.

⚙️ Technology Stack
Tool	Purpose
Python	Core programming language
Streamlit	Web-based UI and interactivity
Tavily API	Fetches market and competitor data
Matplotlib	Visual data representation
dotenv	Securely loads environment variables
Regex (re)	Cleans and extracts numeric data

🧠 How It Works

Enter a product name (e.g., “Nexus Smartwatch Pro 2”).

The app uses Tavily API to search for real-time competitor data.

It extracts features, prices (in PKR), and reviews.

Generates a visual comparison report with bar and pie charts.
