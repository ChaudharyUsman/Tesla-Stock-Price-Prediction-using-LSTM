# Tesla Stock Price Prediction using LSTM

## Overview
This project aims to analyze and forecast Tesla's stock prices using Long Short-Term Memory (LSTM), a type of recurrent neural network (RNN) well-suited for time series forecasting. By leveraging historical stock data, we build a predictive model to estimate future stock prices.

## Problem Statement
Stock price prediction is a challenging task due to market volatility, external influences, and complex patterns in historical data. Traditional statistical models often fail to capture the long-term dependencies in stock trends. This project uses deep learning techniques to improve accuracy in forecasting Tesla's closing prices.

## Solution Approach
1. **Data Collection & Preprocessing**
   - Load historical Tesla stock data (2000-2025).
   - Clean and preprocess the dataset.
   - Normalize stock prices for better model training.

2. **Exploratory Data Analysis (EDA)**
   - Visualizing stock trends.
   - Identifying patterns and seasonality.

3. **Model Building**
   - Using LSTM to capture temporal dependencies.
   - Implementing dropout layers to prevent overfitting.
   - Training the model with a limited number of epochs for efficient computation.

4. **Evaluation & Prediction**
   - Testing the model on unseen data.
   - Measuring performance using Mean Squared Error (MSE).
   - Forecasting future stock prices.

## Dataset Details
- **Source:** Historical daily stock prices of Tesla (2000-2025).
- **Features:** Date, Open, High, Low, Close, Adjusted Close, Volume.
- **Target Variable:** Closing Price.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, TensorFlow/Keras, Scikit-learn
- **Deep Learning Model:** LSTM
- **IDE:** Jupyter Notebook

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tesla-stock-lstm.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tesla-stock-lstm
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Train the model and make predictions using the provided notebook.

## Results & Future Improvements
- The model provides reasonable predictions based on historical data.
- Further improvements can be made by:
  - Increasing training data.
  - Fine-tuning hyperparameters.
  - Using additional external factors like financial news sentiment analysis.

---
### **Contributions**
Feel free to contribute by submitting a pull request!

### **License**
This project is open-source under the MIT License.
![image](https://github.com/user-attachments/assets/f85278bf-c85b-47f7-9cea-ac65ac03e048)
![image](https://github.com/user-attachments/assets/30f19eec-d038-4725-9cc4-a5e2e6ae7452)
![image](https://github.com/user-attachments/assets/b153b85b-c869-4081-b380-1b07f8992369)
![image](https://github.com/user-attachments/assets/e8c41288-1ad2-4372-984b-1233fadf4d3c)
![image](https://github.com/user-attachments/assets/21e6e6d9-bbc8-4ee4-875f-09ae4ec2d73f)






