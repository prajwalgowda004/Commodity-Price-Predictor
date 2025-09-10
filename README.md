# Commodity Price Predictor
A machine learning-based project for predicting commodity prices using LSTM (Long Short-Term Memory) and Moving Average models. The prediction considers various factors like seasonality, weather conditions, transportation, and market trends to provide an accurate price forecast.

# **Dataset**
The dataset used contains 8208 rows representing commodity price data for vegetables. The data captures key aspects influencing commodity prices over time.
# **Features Considered**
* Seasonality and trends
* Weather conditions
* Consumer preferences
* Transportation and supply chain efficiency
* Market trends and demand spikes

# **Project Structure**
The project includes:
* commodity_price_predictor.ipynb: Core notebook containing data preprocessing, model training, and evaluation for the LSTM model.
* Main.ipynb: Web interface implementation using Flask for interactive predictions.
* Dataset folder: Includes the cleaned data for commodity price predictions.
  
# **Requirements**
To run this project, ensure you have the following dependencies installed:
* Python 3.x
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow/Keras
* Flask
* Seaborn

# **Model Development**
Moving Average Model
* The moving average technique smooths out fluctuations in time-series data by calculating the average of different subsets.

LSTM Model
* LSTM networks are a type of recurrent neural network capable of learning long-term dependencies, particularly useful for time-series data.

Model Evaluation Metrics:
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

Web Interface
The project includes a web application developed using Flask.
Features
* Input commodity details and predict prices for the next three days.
* Visual representation of historical and predicted prices.


# **Usage**
* Enter the commodity name and relevant parameters.
* View predicted prices for the next three days.

# **Future Enhancements**
* Include additional machine learning models for improved accuracy.
* Expand the dataset to include diverse commodities.
* Integration with real-time market APIs.
* Enhanced UI for better user experience.

# **Conclusion**
This project demonstrates the application of machine learning for commodity price prediction using LSTM and Moving Average models. The interactive web interface allows users to gain insights into market trends and make informed decisions.
