# Stock Sure README

This repository contains a Python script named `stock-sure.py` and an HTML file named `index.html`.

## stock-sure.py

This script uses the `yfinance` library to fetch historical stock data for a given stock ID. It then calculates pivot points and support/resistance levels based on the last two days of trading data.

### How it works

1. The user is prompted to enter a stock code.
2. The script uses the `yfinance.Ticker` method to retrieve the stock's history for the past two days.
3. It extracts the high, low, and close prices from the second-to-last day's data.
4. The pivot point and three support/resistance levels are calculated:
   - Pivot (P)
   - First Support (S1) and Resistance (R1)
   - Second Support (S2) and Resistance (R2)
   - Third Support (S3) and Resistance (R3)
5. The calculated values are printed to the console.

### Requirements

- Python 3.x
- `yfinance` library (`pip install yfinance`)

### Usage

1. Clone this repository or download the files.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the script using `python stock-sure.py`.

## index.html

This is a simple HTML file with the content "Hello Yuanhui World".

---

To create a GitHub README file, you can use this template:
```markdown
# Project Name

[Short description of the project]

## Table of Contents

- [Section 1](#section-1)
- [Section 2](#section-2)

## Section 1

[Description of section 1]

## Section 2

[Description of section 2]
