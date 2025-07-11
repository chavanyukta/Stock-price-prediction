# RNNs for Stock Price Prediction  
*Deep Learning Fundamentals*  

**Author:** Yukta Sanjiv Chavan  
**Student ID:** a1873167  
**The University of Adelaide**  

## Project Overview  
This project investigates the use of Recurrent Neural Networks (RNNs) to predict stock prices, focusing on Google’s stock as a case study. Two RNN architectures, SimpleRNN and Long Short-Term Memory (LSTM), are implemented and compared to forecast opening stock prices using historical data. The study applies data preprocessing including normalization and sequence generation, and evaluates model performance based on prediction accuracy and loss. Results indicate the LSTM model outperforms SimpleRNN by better capturing long-term dependencies in stock price movements.


## Dataset  
- Historical daily stock prices of Google (Alphabet Inc.)  
- Features include Date, Open, High, Low, Close, and Volume  
- Dataset split into training (2012-2016) and testing (early 2017) sets  
- 'Open' price is the primary prediction target  

## Selected Columns for Project  
- Date  
- Open (normalized for model input)  
- High  
- Low  
- Close  
- Volume  

## Dataset Source  
The dataset was obtained from publicly accessible financial market sources providing historical stock data for Google (Alphabet Inc.).

## Project Structure  
rnn.ipynb # Jupyter notebook with model training and evaluation
─ data/ # Folder containing the stock price dataset files
─ report.pdf # Full project report including methodology and results
─ README.md # Project documentation file
─ requirements.txt # List of required Python libraries
