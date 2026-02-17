# Gold Price Prediction using LSTM (Time-Series Forecasting)

This project builds a deep learning–based time-series forecasting model to predict gold prices using historical market data. The objective was to explore how sequential patterns in financial data can be captured using LSTM networks to generate meaningful price forecasts.

## Problem Statement

Gold prices fluctuate due to macroeconomic indicators, inflation trends, currency movement, and market sentiment. Traditional models struggle to capture temporal dependencies in such data. This project leverages LSTM (Long Short-Term Memory) networks to model sequential patterns and improve prediction accuracy.

## Approach

### 1) Data Understanding & Preprocessing

* Collected historical gold price data
* Cleaned missing values and normalized features
* Structured data into time-series sequences for LSTM input

### 2) Feature Engineering

* Created lag-based sequences
* Prepared training and testing windows
* Scaled data for neural network performance

### 3) Model Development

* Implemented LSTM architecture for time-series prediction
* Trained model on sequential price data
* Evaluated predictions against actual market trends

### 4) Iteration & Optimization

* Tuned sequence length and parameters
* Experimented with model configurations
* Improved performance through repeated testing and validation

## Tech Stack

* Python
* TensorFlow / Keras
* Pandas & NumPy
* Scikit-learn
* Matplotlib
* Google Colab

## Key Highlights

* End-to-end deep learning workflow for financial forecasting
* Applied LSTM to capture temporal dependencies in market data
* Built a structured experimentation pipeline
* Focused on practical predictive insights, not just model training

## AI-Assisted Development (Vibe Coding)

This project was developed using an AI-assisted workflow where AI tools supported:

* debugging model errors
* improving LSTM architecture decisions
* feature engineering exploration
* optimizing preprocessing pipeline

The development remained iterative and logic-driven, with emphasis on understanding model behavior and validating predictions.

## Project Structure

* `gold_price_prediction(2).ipynb` — data preprocessing, LSTM modeling, evaluation, and visualization
* Dataset — historical gold price time-series data

## Results & Insights

* LSTM effectively captured sequential trends in gold price movements
* Predictions followed realistic directional patterns
* Highlighted importance of time-window selection and scaling in deep learning models

## Future Improvements

* Add multivariate inputs (inflation, USD index, interest rates)
* Try GRU / Transformer-based forecasting
* Deploy as an interactive dashboard
* Automate retraining using live market data

## Author

Built as part of hands-on exploration in machine learning, time-series forecasting, and AI-driven development.

