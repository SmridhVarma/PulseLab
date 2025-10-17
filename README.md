# PulseLab

> Bitcoin Price Prediction - done in style

## About The Project

**PulseLab** is a comprehensive data science project focused on forecasting the price of Bitcoin (BTC-USD). This repository explores, implements, and evaluates a wide array of time-series forecasting models, ranging from classical statistical methods to advanced deep learning and gradient-boosting ensembles.

The primary goal is to identify the most accurate and reliable model for short-term price prediction by comparing their performance on a hold-out test set. The project culminates in a demonstration UI that showcases the predictive power of the top-performing models.

## Models Implemented

This analysis provides a comparative leaderboard for the following models:

  * **Statistical Models:**
      * ARIMA (Autoregressive Integrated Moving Average)
      * SARIMA (Seasonal ARIMA)
      * Holt-Winters
  * **Machine Learning Models:**
      * LightGBM (Light Gradient Boosting Machine)
      * XGBoost
      * CatBoost
      * Random Forest
  * **Deep Learning Models:**
      * ANN (Artificial Neural Network - MLP)
      * LSTM (Long Short-Term Memory)
      * SimpleRNN

Based on the analysis, **LightGBM** was identified as the top-recommended model due to its superior accuracy (lowest MAPE) and excellent generalization, showing no signs of overfitting.

## Project Structure

```
PulseLab/
├── BTC-USD_2022-06-30_to_2025-09-30.csv  # The primary dataset used for training and testing
├── Capstone_Finalized.ipynb             # Main Jupyter Notebook with all model implementations
├── Demo_Capstone_UI_+_Tree_Based_Models.ipynb # Notebook for the demo UI (likely Streamlit/Gradio)
├── requirements.txt                     # All Python dependencies needed to run the project
├── LICENSE                                # MIT License
└── README.md                              # You are here!
```

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

  * Python 3.8 or higher
  * Jupyter Notebook or Jupyter Lab or colab works too!

### Installation

1.  **Clone the repo**
    ```sh
    git clone https://github.com/SmridhVarma/PulseLab.git
    ```
2.  **Navigate to the project directory**
    ```sh
    cd PulseLab
    ```
3.  **Install the required packages**
    ```sh
    pip install -r requirements.txt
    ```

### Running the Project

You can explore the complete analysis or run the UI demo - refer to the demo vid to get a feel of the end product.

1.  **To see the full analysis and model comparisons:**

      * Launch Jupyter Notebook:
        ```sh
        jupyter notebook
        ```
      * Open `Capstone_Finalized.ipynb`.

2.  **To run the UI demonstration:**

      * Launch Jupyter Notebook:
        ```sh
        jupyter notebook
        ```
      * Open `Demo_Capstone_UI_+_Tree_Based_Models.ipynb` and run the cells.

## License

Distributed under the MIT License. See `LICENSE` for more information.
