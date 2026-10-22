# TCS Stock Price Prediction Using Machine Learning

## About the Project

This project explores stock price prediction for **Tata Consultancy Services (TCS)** using Python and machine learning. Historical stock market data is retrieved using the `yfinance` library, analysed using Python data science libraries, and used to experiment with a Random Forest model.

The project demonstrates a basic machine learning workflow, from collecting historical data to preparing data and exploring predictive modelling.

## Objectives

- Retrieve historical TCS stock market data.
- Explore and analyse stock price trends.
- Prepare data for machine learning.
- Apply a Random Forest model for stock price prediction.
- Understand the fundamentals of machine learning using financial data.

## Technologies Used

- **Python** — Programming and data processing
- **yfinance** — Retrieving historical stock market data
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualisation
- **Scikit-learn** — Machine learning model implementation

## Machine Learning Model

The project uses a **Random Forest Regressor** to explore the relationship between historical stock data and stock price predictions.

Random Forest is an ensemble learning algorithm that combines predictions from multiple decision trees to produce a final prediction.

## Project Workflow

1. **Data Collection:** Retrieve historical TCS stock market data using `yfinance`.
2. **Data Exploration:** Inspect and understand the available stock market data.
3. **Data Preparation:** Prepare the dataset for machine learning.
4. **Model Development:** Apply a Random Forest model for stock price prediction.
5. **Prediction and Analysis:** Examine the model's predictions and analyse the results.

## Getting Started

### Prerequisites

Basic familiarity with Python and Jupyter Notebook or Google Colab is recommended.

### Installation

Install the required libraries using pip:

```bash
pip install yfinance pandas numpy matplotlib scikit-learn
```

### Run the Project

1. Clone or download this repository.
2. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Install any missing dependencies.
4. Run the notebook cells sequentially.

## Dataset

Historical stock market data for Tata Consultancy Services (TCS) is retrieved using `yfinance`. The dataset includes market information returned by the library for the selected ticker and date range.

## Learning Outcomes

- Working with financial time-series data using Python.
- Using Pandas and NumPy for data preparation.
- Exploring stock market trends through visualisation.
- Applying a Random Forest model to a prediction problem.
- Understanding the basic workflow of a machine learning project.

## Limitations

Stock prices are influenced by numerous factors, including market conditions, economic events and company performance. A model trained on historical prices cannot reliably predict all future movements. Predictions from this project are experimental and should not be treated as financial advice.

## Author

**Siddhi P. Malvankar**  
Information Technology Engineering Student

[LinkedIn Profile](https://www.linkedin.com/in/siddhi-p-malvankar)

---

*This project was developed for educational purposes to explore Python-based data analysis and machine learning.*
