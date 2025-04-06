
## 🔍 Project Motivation & Business Questions

This project explores the behavior of three major cryptocurrencies—Bitcoin, Ethereum, and Dogecoin—across multiple market metrics. It aims to uncover insights through visual analytics and data science techniques.

### Key Business Questions

1. Which crypto showed the highest volatility in 2021?
2. Did trading volume trends align with price surges?
3. Do Bitcoin, Ethereum, and Dogecoin move together?
4. Which asset experienced the greatest relative growth in 2021?
5. Is there consistent investor interest in Dogecoin, or was it just hype?


README FILE FOR CRYPTO PROJECT
📊 Crypto Volatility Analysis
This project performs an exploratory data analysis (EDA) on a cleaned dataset of historical cryptocurrency prices. The goal is to examine price trends, verify historical claims, and provide a foundation for deeper analysis on market behavior.
________________________________________
📁 Project Structure
Crypto-Volatility-Analysis/
├── README.md                            <- Overview of the project
├── Crypto_Analysis_for_Git.ipynb        <- Main analysis notebook
└── requirements.txt                     <- Python dependencies (optional)
________________________________________
📌 Dataset
•	Source: Top 50 Cryptocurrencies Historical Data – Kaggle
•	This dataset contains daily open, high, low, close, and volume data for 50 cryptocurrencies.
________________________________________
🚀 Getting Started
1.	Clone the repository or download the files.
2.	Download the original dataset from Kaggle and clean it using your own script or use the provided cleaned_crypto_data.csv.
3.	Launch Crypto_Analysis_for_Git.ipynb in Jupyter or Google Colab.
4.	Ensure the CSV is in the same directory or update the file path in the notebook.
________________________________________
📈 Features of the Notebook
•	Load and inspect cleaned historical data
•	Verify price history for specific timeframes (e.g. April 2021 for Bitcoin)
•	Visualize price trends using line plots
________________________________________
📌 Notes
•	This notebook avoids Google Drive/Colab-specific dependencies to ensure reproducibility.
•	For full transparency, consider adding a data-wrangling notebook that shows how you cleaned the original dataset.
________________________________________

________________________________________
🛠 How to Run This Project

To run this project on your local machine:

1. Clone or download the repository.
2. Ensure you have Python 3.x installed.
3. (Optional but recommended) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Open the notebook:

```bash
jupyter notebook Crypto_Analysis_for_Git.ipynb
```


## 📘 Blog Post

Check out the full write-up on Medium:  
[What Can We Learn from Price, Volume, and Volatility in Crypto?](https://medium.com/@stephen.senteio/what-can-we-learn-from-price-volume-and-volatility-in-crypto-f33900f2d690)
_______________________________________
🧠 Author
•	Project by [Steve Senteio]
________________________________________
📃 License
This project is for educational purposes. Please check the original dataset license on Kaggle before redistributing.

