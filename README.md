

# Hybrid Stock Market Forecasting

# Overview

This project focuses on forecasting stock market trends using a hybrid approach. The dataset used for this project includes various files providing information on daily stock prices, stock splits adjustments, company descriptions, and fundamental metrics extracted from annual SEC 10K filings.

# Dataset

- **prices.csv**: Raw, as-is daily prices. Spans from 2010 to the end of 2016. For newer companies, the date range is shorter. Approximately 140 stock splits occurred during this period, but this set doesn't account for those splits.
  
- **prices-split-adjusted.csv**: Similar to prices.csv, but with adjustments for stock splits.

- **securities.csv**: General description of each company with a division into sectors.

- **fundamentals.csv**: Metrics extracted from annual SEC 10K filings (2012-2016), providing ample information to derive popular fundamental indicators.

- Algorithm used : RNN,LSTM,GRU


![Lstm](https://github.com/Pk7372singh/hybrid-stock-market-forcasting/assets/92020279/3fb8b5c0-220e-4d8f-bd7e-cc54b70e8eaa)

![gru](https://github.com/Pk7372singh/hybrid-stock-market-forcasting/assets/92020279/25ca5100-1049-4bee-a896-be9f19f738bf)

### Pr![activation](https://github.com/Pk7372singh/hybrid-stock-market-forcasting/assets/92020279/9f106e0f-26e9-4a15-9f1e-ba2e63327d80)


Make sure you have the following libraries installed:


- pip install numpy pandas matplotlib
```

### Usage

```python
# Importing important libraries
import numpy as np
import pandas as pd
import os
import matplotlib.pyplot as plt

# Calling the file in nyse named prices.csv
df = pd.read_csv("prices.csv", header=0)
```
![Screenshot 2024-01-26 153431](https://github.com/Pk7372singh/hybrid-stock-market-forcasting/assets/92020279/f238de1a-6bab-4e30-ae2d-c859831649cb)


![Screenshot 2024-01-26 153458](https://github.com/Pk7372singh/hybrid-stock-market-forcasting/assets/92020279/a0a12df5-faae-4edd-a785-0d4264f3efdd)
