# Cryptocurrency Price Predictor

This repository contains a Jupyter Notebook (`crypto_price_prediction.ipynb`) demonstrating the prediction of cryptocurrency prices using a Long Short-Term Memory (LSTM) neural network.

### Overview:
- **Data Collection:** The notebook fetches historical cryptocurrency price data from the CryptoCompare API.
- **Data Preprocessing:** It preprocesses the data by scaling and sequencing it for input into the neural network.
- **Model Building:** An LSTM neural network is built, trained, and evaluated to capture temporal dependencies in the time series data.
- **Prediction:** The trained model is used to iteratively predict cryptocurrency prices for the next several days.
- **Visualization:** Historical prices are plotted along with the predicted prices for better visualization and analysis.

### How to Use:
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/nirnaim/crypto-price-predictor.git
   ```
1. **Open the Jupyter Notebook:**
   - Navigate to the repository directory.
   - Open `crypto_price_prediction.ipynb` in Jupyter Notebook or Jupyter Lab.
2. **Follow the Steps:**
   - Execute each cell in the notebook to collect data, preprocess it, train the model, and make predictions.

### Dependencies:
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `tensorflow` or `keras`

### Contributions:
Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or bug fixes.

### License:
This project is licensed under the MIT License.
