# Crypto Token Correlation Heatmap

This project provides a framework for analyzing and visualizing the correlation between multiple cryptocurrency tokens using historical price data from the CoinGecko Pro API. Users can dynamically select any set of tokens, fetch their price histories, compute correlations and volatilities, and visualize these relationships with heatmaps.

## Features

- **Dynamic Token Selection:** Input any list of token IDs (e.g., `bitcoin`, `ethereum`, `solana`) for analysis.
- **Automated Data Fetching:** Retrieves historical price data from the CoinGecko Pro API.
- **Data Alignment:** Resamples and aligns price data to a common time interval for accurate correlation analysis.
- **Correlation Heatmap:** Visualizes the correlation matrix between selected tokens using Seaborn and Matplotlib.
- **Volatility Analysis:** Computes and displays the volatility (standard deviation of log returns) for each token.
- **Efficient Data Storage:** Uses `joblib` for fast saving and loading of large DataFrames.

## Getting Started

### Prerequisites

- Python 3.7+
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/token-heatmap.git
   cd token-heatmap
   ```

2. **Set up your `.env` file** with your CoinGecko Pro API key:
   ```
   GECKO_API=your_api_key_here
   ```

3. **Run the Jupyter Notebooks** in the `Notebooks/` directory:
   - `01_data.ipynb`: Fetch and store historical price data for your chosen tokens.
   - `token_correlation.ipynb`: Load the data, compute correlations and volatilities, and visualize the results.

## Usage

### - Fetch Price Data

### - Save and Load Data

### - Visualize Correlation Heatmap

### - Compute Volatility



## License

MIT License

---

**Feel free to fork,