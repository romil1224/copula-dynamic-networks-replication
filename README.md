# Nifty 50 Stock Returns Dataset (2017–2025)

## Overview

This repository contains daily stock return data for 49 constituents of the Nifty 50 index, used in the research paper:

**Copula-Based Dynamic Networks for Financial Volatility Forecasting in the Indian Markets**

**Authors:** Romil Malhotra and Niladri Chatterjee  
**Affiliation:** Department of Mathematics, Birla Institute of Technology and Science (BITS) Pilani, Pilani Campus, India.

The dataset is intended to support research and replication of empirical analyses involving financial volatility forecasting, copula-based dependence modelling, and dynamic financial networks.

## Dataset Description

- **Number of stocks:** 49
- **Market:** Indian equity market (Nifty 50)
- **Frequency:** Daily
- **Sample period:** 20 November 2017 – 31 December 2025
- **Format:** CSV
- **Variables:** Daily stock returns

Each CSV file contains the daily return observations for an individual stock.

## Data Source

The underlying historical stock price data were obtained from Yahoo Finance:

https://finance.yahoo.com/

Daily returns were calculated from historical stock prices using:

\[
r_{i,t}=\ln\left(\frac{P_{i,t}}{P_{i,t-1}}\right)
\]

where:

- \(r_{i,t}\) denotes the log return of stock \(i\) on day \(t\).
- \(P_{i,t}\) denotes the closing price of stock \(i\) on day \(t\).
- \(P_{i,t-1}\) denotes the previous trading day's closing price.

## Repository Structure

```text
.
├── README.md
├── RELIANCE.NS.csv
├── TCS.NS.csv
├── INFY.NS.csv
├── HDFCBANK.NS.csv
└── ... (49 stock return files)
```

Each CSV file corresponds to one stock and contains its daily return time series.

## Intended Use

The dataset was assembled for research on:

- Financial volatility forecasting
- Copula-based dependence modelling
- D-vine copula networks
- Copula mutual information and entropy
- Network log-ARCH models
- Cross-sectional dependence in equity markets

## Citation

If you use this dataset, please cite the associated research paper:

Malhotra, R., & Chatterjee, N. *Copula-Based Dynamic Networks for Financial Volatility Forecasting in the Indian Markets*.

Please update this citation with the journal, publication year, volume, pages, and DOI when available.

## Data Disclaimer

The underlying historical price data were sourced from Yahoo Finance. The return series are derived from those price observations and are provided for academic research and reproducibility purposes.

Users should independently verify the accuracy, completeness, and suitability of the data for their intended applications. The authors do not guarantee the accuracy or completeness of the underlying third-party source data.

Please consult Yahoo Finance's applicable terms of use before redistributing or reusing the underlying data.

## Authors

**Romil Malhotra**  
Department of Mathematics, BITS Pilani  
ORCID: https://orcid.org/0009-0003-5296-6149

**Niladri Chatterjee**  
Department of Mathematics, BITS Pilani  
ORCID: https://orcid.org/0000-0003-3832-4003
