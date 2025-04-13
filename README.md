Stock Data Analysis Project
This project demonstrates how to extract, process, and visualize stock data for Tesla and GameStop using Python. The project includes extracting historical stock data using the yfinance library and revenue data using web scraping techniques. The project also includes the creation of interactive graphs to visualize the stock data and revenue trends.

Project Overview
Extract Tesla Stock Data using the yfinance library and save it in a DataFrame.

Extract Tesla Revenue Data using web scraping from an HTML page.

Extract GameStop Stock Data using the yfinance library.

Extract GameStop Revenue Data using web scraping from an HTML page.

Visualize Tesla Stock and Revenue using interactive graphs.

Visualize GameStop Stock and Revenue using interactive graphs.

Filter Data up to June 2021 and graph stock data accordingly.

Libraries Used
yfinance: To fetch historical stock data.

requests: For downloading web pages.

beautifulsoup4: For web scraping.

pandas: For data manipulation.

plotly: For creating interactive graphs.

Installation
To get started with the project, clone the repository and install the required dependencies.

Step 1: Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/stock-data-analysis.git
cd stock-data-analysis
Step 2: Install Dependencies
Make sure you have pip installed. Then, install the required libraries by running:

bash
Copy
Edit
pip install -r requirements.txt
Or install libraries individually using pip:

bash
Copy
Edit
pip install yfinance requests beautifulsoup4 pandas plotly
Step 3: Run the Jupyter Notebook
Open the Jupyter notebook in your preferred IDE (like VS Code or Jupyter Notebook):

bash
Copy
Edit
jupyter notebook
Step 4: Follow the Notebook Instructions
Open the notebook (Stock_Data_Analysis.ipynb) and follow the steps to load data, process it, and visualize the results.

Features
Tesla Stock Data Extraction: The project fetches stock data for Tesla using yfinance.

Tesla Revenue Data Scraping: Revenue data for Tesla is scraped from an HTML webpage and stored in a DataFrame.

GameStop Stock Data Extraction: The project fetches stock data for GameStop using yfinance.

GameStop Revenue Data Scraping: Revenue data for GameStop is scraped from an HTML webpage and stored in a DataFrame.

Interactive Graphs: The project visualizes stock and revenue data using interactive graphs created with plotly.

Data Filtering: The stock and revenue data is filtered to show data only up until June 2021.

Screenshots
Here are a few screenshots from the project:

Tesla Stock Data: Displays stock data for Tesla, showing price trends.

GameStop Stock Data: Displays stock data for GameStop, showing price trends.

Tesla Revenue Graph: Visualizes Tesla's revenue data.

GameStop Revenue Graph: Visualizes GameStop's revenue data.

How to Contribute
Feel free to contribute to this project by submitting issues, suggestions, or pull requests. If you find a bug or want to add a feature, open an issue or create a pull request with a description of your changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.
