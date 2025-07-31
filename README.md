# Strategic Investing with Python & Pandas

This project showcases three quantitative investment strategy notebooks developed in Python using `pandas`, `yfinance`, and `Jupyter Notebook`. The strategies are based on data pulled from Yahoo Finance and leverage metrics from the S&P 500. The output is displayed in well-formatted Excel spreadsheets for easy analysis and portfolio planning.

All notebooks are based on educational resources from the nonprofit [freeCodeCamp](https://www.freecodecamp.org/), extended with my own implementation and improvements.

---

## Project Overview

### 1. `Equal_Weight_Strategy.ipynb`
- Filters the top 50 S&P 500 stocks.
- Calculates the number of shares to buy for each stock with a user-defined portfolio size.
- Outputs a neatly formatted Excel file.

### 2. `Quantitative_Momentum_Strategy.ipynb`
- Ranks all S&P 500 stocks based on historical momentum over:
  - 1-month
  - 3-month
  - 6-month
  - 12-month periods.
- Builds a momentum score and sorts accordingly.

### 3. `Quantitative_Value_Strategy.ipynb`
- Scores and ranks S&P 500 stocks based on five valuation metrics:
  - **P/E** (Price-to-Earnings)
  - **P/S** (Price-to-Sales)
  - **P/B** (Price-to-Book)
  - **EV/EBITDA** (Enterprise Value to EBITDA)
  - **EV/GP** (Enterprise Value to Gross Profit)

---

## ⚙Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/learn-strategic-investing.git
cd learn-strategic-investing
```

### 2. Create & activate a virtual environment (optional but recommended)

```bash
conda create -n investing-env python=3.10
conda activate investing-env
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any of the three notebooks and follow the instructions in the cells.

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

**Nathan Bell**  
Developed as part of an applied finance and programming learning journey.

---

## Acknowledgements

- [freeCodeCamp](https://www.freecodecamp.org/) — For inspiring the project with their Quantitative Investing tutorials.
- [Yahoo Finance](https://finance.yahoo.com/) — For financial data.

```txt
pandas
numpy
yfinance
openpyxl

