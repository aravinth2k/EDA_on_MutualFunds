# Exploratory Data Analysis on Mutual Funds

This repository contains the code and analysis for an exploratory data analysis (EDA) project on mutual funds. The project focuses on collecting data from the Groww platform using Python, cleaning the data, and performing various analyses to gain insights into mutual fund types, expense ratios, returns, and constructing a diversified mutual fund portfolio.

## Project Overview

- **Data Collection**: Data was collected from the Groww platform using the `requests`, `bs4`, and `json` libraries in Python.

- **Data Cleaning**: The collected data was cleaned by removing duplicates, handling missing values, extracting relevant text data, and dropping unnecessary columns.

- **Analysis Highlights**:
  - Number of Asset Management Companies (AMCs) in India.
  - Top AMCs based on the number of funds managed.
  - Analysis of different mutual fund types and their distributions.
  - Expense ratio analysis to understand the cost of different fund types.
  - Return analysis and exploration of the relationship between expense ratios and returns.
  - Selection of funds with good performance based on expense ratio and return.
  - Construction of a diversified mutual fund portfolio to maximize return.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/aravinth2k/EDA_on_MutualFunds
   cd EDA_on_MutualFunds

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt

3. Run the Jupyter Notebook files in the notebooks directory to see the step-by-step analysis.

4. The `data` directory contains the raw data collected from Groww.

5. The `results` directory includes visualizations and Presentation `EDA Mutual Fund.pptx` have insights generated from the analysis.

Feel free to explore the code, adapt it to your needs, and contribute to the project.

## Results and Visualizations

Top AMCs based on the number of funds managed.
![newplot (3)](https://github.com/aravinth2k/EDA_on_MutualFunds/assets/71697881/123d2ab6-5bbd-4384-a0df-3c581af76f7d)

Top Equity Funds based on Fund Performance.
![newplot (8)](https://github.com/aravinth2k/EDA_on_MutualFunds/assets/71697881/e1d43ca9-bc98-406a-8aba-553acbd742a6)

## Conclusion

This project provides valuable insights into mutual funds' landscape, including fund types, expenses, and returns. The analysis helps investors make informed decisions about fund selection and portfolio construction.

## Contributors

    Aravinth B (https://github.com/aravinth2k)
    Naga Babu K

## License

This project is licensed under the MIT License.
