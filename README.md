# Gold Price Prediction using LSTM (Long Short-Term Memory Networks)

# 📊 Dataset Description:
File Used: gold.csv (loaded in the notebook)

Total Records: 1,718

Time Range:

Train Set: Nov 5, 2011 – Jul 27, 2017

Test Set: Jul 28, 2017 – Dec 31, 2018

Target Variable: Gold price

Features Used: adj closing price, etc. 

# 🧠 ML/DL Techniques Used:
LSTM (Long Short-Term Memory) neural network

Scaled data using MinMaxScaler

Converted time series data to supervised format using a sliding window

# 🛠️ Tech Stack:
Python (Jupyter Notebook)

Pandas, NumPy, Matplotlib, Seaborn

TensorFlow / Keras

Scikit-learn

# ✅ Steps Performed:
Data loading and preprocessing

Exploratory Data Analysis (EDA)

Feature scaling

Data reshaping for LSTM input

Model building and training using LSTM

Prediction on test set

Performance evaluation using RMSE or MAPE

Visualization of predictions vs actual values

# 📈 Results:
Achieved decent prediction performance with LSTM model

Visualized the gold price trend and model accuracy

# 🤖 Future Improvements:
Incorporate additional features like oil price, stock indices, or economic indicators

Try other models: GRU, Bidirectional LSTM, or Transformers

Hyperparameter tuning and dropout regularization

