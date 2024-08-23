# Bitcoin Price Prediction Using LSTM
This project implements a Long Short-Term Memory (LSTM) neural network to predict Bitcoin prices in CAD using historical data. The model is trained and evaluated on data fetched from the CryptoCompare API.

## Model Architecture
The model is built using the Keras library with the following architecture:
* LSTM layer with 100 neurons
* Dropout layer with a rate of 0.2
* Dense layer with linear activation

# Training and Evaluation
* The data is split into training and testing sets with an 80-20 ratio.
* The model is trained for 20 epochs with a batch size of 32.
* The Mean Squared Error (MSE) is used as the loss function, and the Adam optimizer is employed.

# Results
* Mean Absolute Error (MAE): 0.0429
* Mean Squared Error (MSE): 0.00308
* R² Score: 0.655
