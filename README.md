
# Global Stock Market Datasets

## Overview

This repository contains five stock market datasets from different countries/regions:

1. India
2. United States
3. United Kingdom
4. Japan
5. Hong Kong

Each dataset contains historical daily stock price data for 10 major companies from the corresponding market. The datasets are suitable for:

* Portfolio optimization
* Bayesian optimization research
* Machine learning and prediction tasks
* Financial data analysis
* Time series forecasting
* Risk-return analysis
* Reinforcement learning applications in finance

---

# Dataset Details

## 1. Indian Stock Market Dataset

**File Name:** `Indian_10.csv`

### Description

Historical daily stock prices of 10 major Indian companies listed on the National Stock Exchange (NSE).

### Features

| Column Name   | Description               |
| ------------- | ------------------------- |
| Date          | Trading date              |
| TCS.NS        | Tata Consultancy Services |
| INFY.NS       | Infosys                   |
| RELIANCE.NS   | Reliance Industries       |
| HDFCBANK.NS   | HDFC Bank                 |
| LT.NS         | Larsen & Toubro           |
| HINDUNILVR.NS | Hindustan Unilever        |
| ASIANPAINT.NS | Asian Paints              |
| COALINDIA.NS  | Coal India                |
| NTPC.NS       | NTPC Limited              |
| TATAMOTORS.NS | Tata Motors               |

### Dataset Shape

* Rows: 2465
* Columns: 11

---

## 2. USA Stock Market Dataset

**File Name:** `USA_10.csv`

### Description

Historical daily stock prices of 10 major U.S. companies.

### Features

| Column Name | Description       |
| ----------- | ----------------- |
| Date        | Trading date      |
| AMZN        | Amazon            |
| META        | Meta Platforms    |
| GOOG        | Alphabet (Google) |
| BA          | Boeing            |
| TSLA        | Tesla             |
| AAPL        | Apple             |
| WMT         | Walmart           |
| NFLX        | Netflix           |
| XOM         | Exxon Mobil       |
| JNJ         | Johnson & Johnson |

### Dataset Shape

* Rows: 2517
* Columns: 11

### Note

The `META` column may contain missing values in earlier years because Facebook/Meta was listed later.

---

## 3. UK Stock Market Dataset

**File Name:** `UK_10.csv`

### Description

Historical daily stock prices of 10 major companies listed in the United Kingdom.

### Features

| Column Name | Description          |
| ----------- | -------------------- |
| Date        | Trading date         |
| BARC.L      | Barclays             |
| BP.L        | BP                   |
| BHP.L       | BHP Group            |
| AZN.L       | AstraZeneca          |
| VOD.L       | Vodafone             |
| TSCO.L      | Tesco                |
| RR.L        | Rolls-Royce Holdings |
| NG.L        | National Grid        |
| ULVR.L      | Unilever             |
| BBY.L       | Balfour Beatty       |

### Dataset Shape

* Rows: 2528
* Columns: 11

---

## 4. Japan Stock Market Dataset

**File Name:** `Japan_10.csv`

### Description

Historical daily stock prices of 10 major Japanese companies listed on the Tokyo Stock Exchange.

### Features

| Column Name | Description                    |
| ----------- | ------------------------------ |
| Date        | Trading date                   |
| 7203.T      | Toyota Motor Corporation       |
| 6758.T      | Sony Group                     |
| 8306.T      | Mitsubishi UFJ Financial Group |
| 4502.T      | Takeda Pharmaceutical          |
| 3382.T      | Seven & i Holdings             |
| 9432.T      | Nippon Telegraph and Telephone |
| 1802.T      | Obayashi Corporation           |
| 9501.T      | Tokyo Electric Power Company   |
| 3407.T      | Asahi Kasei                    |
| 5401.T      | Nippon Steel                   |

### Dataset Shape

* Rows: 2468
* Columns: 11

---

## 5. Hong Kong Stock Market Dataset

**File Name:** `HongKong_10.csv`

### Description

Historical daily stock prices of 10 major Hong Kong listed companies.

### Features

| Column Name | Description                           |
| ----------- | ------------------------------------- |
| Date        | Trading date                          |
| 0700.HK     | Tencent Holdings                      |
| 0005.HK     | HSBC Holdings                         |
| 0016.HK     | Sun Hung Kai Properties               |
| 0857.HK     | PetroChina                            |
| 0941.HK     | China Mobile                          |
| 0241.HK     | Alibaba Health Information Technology |
| 0175.HK     | Geely Automobile                      |
| 1099.HK     | Sinopharm Group                       |
| 1299.HK     | AIA Group                             |
| 0027.HK     | Galaxy Entertainment Group            |

### Dataset Shape

* Rows: 2466
* Columns: 11

---

# Data Format

* The first column (`Date`) represents the trading date.
* Remaining columns represent daily stock prices.
* All datasets are stored in CSV format.
* Missing values may exist due to market holidays, listing dates, or unavailable records.

---

# Applications

These datasets can be used for:

* Portfolio optimization
* Bayesian optimization
* Multi-objective optimization
* Financial forecasting
* Risk management
* Asset allocation
* Deep learning models for finance
* Reinforcement learning in trading
* Comparative international market analysis

---

# Example Usage in Python

```python
import pandas as pd

# Load dataset
india_data = pd.read_csv('Indian_10.csv')

# Display first five rows
print(india_data.head())
```

---

# Citation

If you use these datasets in your research work, please cite the corresponding repository or related publication.

---

# License

This dataset is provided for academic and research purposes.
