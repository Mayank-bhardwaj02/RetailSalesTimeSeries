# Time Series Forecasting on Advance Retail Sales: Clothing and Clothing Accessory Stores (RSCCASN)

## Overview

This repository contains a project that utilizes Long Short-Term Memory (LSTM) and Recurrent Neural Networks (RNN) to forecast Advance Retail Sales in the Clothing and Clothing Accessory Stores sector. The data for this project is sourced from the Federal Reserve Economic Data (FRED).

## Data

The dataset features monthly sales data and is acquired from [FRED Economic Research](https://fred.stlouisfed.org/). This data is instrumental for understanding and forecasting future sales in the Clothing and Clothing Accessory Stores sector.

## Methodology

1. **Data Preprocessing**: The dataset is scaled and transformed to make it suitable for model training.
2. **Model Architecture**: An LSTM-based RNN model is employed for the time series forecasting task.
3. **Training**: The model is trained using a subset of the dataset.
4. **Evaluation**: The model's performance is assessed using a separate test dataset and various metrics.
5. **Forecasting**: The trained model is subsequently used to forecast future sales data.

## Results

The LSTM-based RNN model successfully captures both the underlying trend and seasonality in the data, providing a reliable forecast for future sales in the Clothing and Clothing Accessory Stores sector.

## Acknowledgments

Special thanks to FRED Economic Research for making the dataset publicly available.

