# Stock News Sentiment Analysis and Price Prediction

## Project Overview

This project is a comprehensive Python application that integrates various libraries and technologies to analyze financial news sentiment and predict stock prices. The application includes the following functionalities:
- **Web scraping** financial news articles using `BeautifulSoup`.
- **Natural Language Processing (NLP)** to perform sentiment analysis on news headlines using `nltk`.
- **Stock price prediction** using machine learning models implemented with `scikit-learn`, `PyTorch`, and `TensorFlow`.
- **Data visualization** with `Matplotlib`, `Seaborn`, and `Plotly`.
- **Database management** with `SQLite` and `SQLAlchemy`.
- **Web application** interfaces built with `Streamlit`, `Flask`, and `FastAPI`.

## Features

- **Financial News Scraper**: Collects real-time financial news and stores it in CSV format.
- **Sentiment Analysis**: Processes the scraped headlines to determine sentiment (positive, neutral, or negative).
- **Stock Price Prediction**: Uses historical stock data to predict future stock prices using machine learning algorithms.
- **Interactive Web App**: A user-friendly interface where users can view the news, sentiment analysis, and stock predictions.
  
## Libraries Used

This project includes a wide array of important Python libraries:
- **Streamlit**: For creating the web app.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For visualizing data.
- **Plotly**: For creating interactive plots.
- **Django & Flask**: For web application development.
- **NLTK**: For natural language processing tasks.
- **Scikit-learn**: For building machine learning models.
- **PyTorch & TensorFlow**: For deep learning models.
- **Statsmodels**: For statistical analysis.
- **BeautifulSoup (bs4)**: For web scraping.
- **FastAPI**: For building fast web APIs.
- **SQLAlchemy & SQLite3**: For managing and querying the database.
- **Requests**: For making HTTP requests.
- **Pytest**: For testing.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/stock-sentiment-analysis.git
    cd stock-sentiment-analysis
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Running the Web App**:
    - For `Streamlit`, run the following command:
      ```bash
      streamlit run app.py
      ```
    - For `Flask`, use:
      ```bash
      flask run
      ```
    - For `FastAPI`, use:
      ```bash
      uvicorn main:app --reload
      ```

2. **Data Scraping**:
   - Run the `scraper.py` script to collect financial news data:
     ```bash
     python scraper.py
     ```

3. **Sentiment Analysis**:
   - Process the collected news data and perform sentiment analysis by running:
     ```bash
     python sentiment_analysis.py
     ```

4. **Stock Price Prediction**:
   - Train the stock price prediction model by running:
     ```bash
     python stock_prediction.py
     ```

## Directory Structure

