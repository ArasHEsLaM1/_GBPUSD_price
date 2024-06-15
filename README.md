# Forex Pairs Dataset Repository

Welcome to the **Forex Pairs Dataset Repository**! This repository contains datasets of various Forex pairs across different timeframes, which can be used for research, analysis, and algorithmic trading.

## Table of Contents

- [**Introduction**](#introduction)
- [**Datasets**](#datasets)
- [**Usage**](#usage)
- [**Installation**](#installation)
- [**Contributing**](#contributing)
- [**License**](#license)
- [**Contact**](#contact)

## Introduction

Forex trading, also known as **foreign exchange trading**, involves the exchange of currencies on a global decentralized market. This repository provides datasets of several Forex pairs in different timeframes (e.g., 1-minute, 5-minute, 15-minute, hourly, daily, etc.). These datasets can be utilized for developing trading strategies, backtesting, and conducting various financial analyses.

## Datasets

The repository includes datasets for the following Forex pairs:

- **EUR/USD**
- **GBP/USD**
- **USD/JPY**
- **AUD/USD**
- **USD/CAD**
- **NZD/USD**
- **USD/CHF**

### Timeframes

Each Forex pair dataset is available in the following timeframes:

- **1-Minute**
- **5-Minute**
- **15-Minute**
- **30-Minute**
- **1-Hour**
- **4-Hour**
- **Daily**

## Usage

The datasets are stored in CSV format for easy access and manipulation. Each CSV file contains the following columns:

- **Timestamp**: The date and time of the data point.
- **Open**: The opening price at the specified timeframe.
- **High**: The highest price during the specified timeframe.
- **Low**: The lowest price during the specified timeframe.
- **Close**: The closing price at the specified timeframe.
- **Volume**: The trading volume during the specified timeframe.

### Example

Here is an example of how to read and use the dataset in Python:

```python
import pandas as pd

# Load the dataset
data = pd.read_csv('path_to_your_dataset.csv')

# Display the first few rows of the dataset
print(data.head())
