

# Hybrid Stock Market Forecasting

# Overview

This project focuses on forecasting stock market trends using a hybrid approach. The dataset used for this project includes various files providing information on daily stock prices, stock splits adjustments, company descriptions, and fundamental metrics extracted from annual SEC 10K filings.

# Dataset

- **prices.csv**: Raw, as-is daily prices. Spans from 2010 to the end of 2016. For newer companies, the date range is shorter. Approximately 140 stock splits occurred during this period, but this set doesn't account for those splits.
  
- **prices-split-adjusted.csv**: Similar to prices.csv, but with adjustments for stock splits.

- **securities.csv**: General description of each company with a division into sectors.

- **fundamentals.csv**: Metrics extracted from annual SEC 10K filings (2012-2016), providing ample information to derive popular fundamental indicators.



### Prerequisites

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

