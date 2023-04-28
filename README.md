# 10708-Project

## Dataset

Kaggle dataset can be found here: [Stock Market Data](https://www.kaggle.com/datasets/paultimothymooney/stock-market-data)

Use `!kaggle datasets download -d paultimothymooney/stock-market-data` to download data.

## Models

Uni-stock CNN + LSTM: Use `stocks_LSTM.ipynb` to load in the csv file of a particular stock, train, and perform inference.

Multi-stock: Use `Graphical_LSTM.ipynb` to load in multiple stocks into a batch and train, visualize, and perform inference. Basic correlation matrix and adjacency graph is implemented.

