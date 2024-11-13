
# Stock Accuracy Prediction with LSTM Model

This project aims to predict stock prices using an LSTM (Long Short-Term Memory) model. It evaluates performance on multiple targets (`Target1`, `Target2`, `Target3`) and provides metrics such as accuracy (DA) and Matthews Correlation Coefficient (MCC) for each stock. The project also includes training and evaluation for multiple stocks, tracking model performance, and visualizing training and validation accuracy using Matplotlib.

## Features

- **Stock Prediction using LSTM**: The model is designed to predict stock prices for multiple stocks with different target variables.
- **Metrics**: Accuracy (DA) and Matthews Correlation Coefficient (MCC) are used to evaluate model performance.
- **Model Checkpointing**: The best model (based on validation accuracy) is saved during training.
- **Visualization**: Training and validation accuracy for each stock and target are visualized after training.

## Requirements

Ensure you have the following libraries installed:

- `tensorflow`: For building and training the LSTM model.
- `matplotlib`: For visualizing training and validation accuracy.
- `sklearn`: For evaluating the model using accuracy and MCC.
  
You can install these dependencies using pip:

```bash
pip install tensorflow matplotlib scikit-learn
