# Stock Market Regime Identification and Prediction Projec
This project explores the potential for identifiaction stock market regime and predicting stock market regimes and backtesting trading strategies based on those predictions. It consists of three Jupyter Notebooks, each focusing on a specific stage of the process:

## 1. Identification Process (identification.ipynb):
   This notebook focuses on data preprocessing and identification feature creation
   
   It includes steps to:
   - Download the stock market dataset from the following URL 
   - Clean and prepare the data for further analysis.
   - Data processing.
   - Perform steps to create financial feature to identify stock regime 
        

        - 
## 2. Prediction Process (prediction.ipynb):
   This notebook focuses on developing a model for predicting market movements.

   It include:
   - Training and evaluating different machine learning models on the prepared data.
   - Selecting the best performing model for predicting future market movements.

## 3. Backtesting Process (backtesting.ipynb):
   This notebook focuses on evaluating the effectiveness of the prediction model in a simulated trading environment.
   It include:
   - Defining trading rules based on the model's predictions.
   - Backtesting the trading strategy on historical data to assess its profitability and risk profile.
   - Analyzing metrics such as win rate, Sharpe Ratio, and Calmar Ratio to evaluate the strategy's performance.



### Getting Started:

1. Download the Project: Clone or download this project repository to your local machine.


2. Install Dependencies: Open a terminal within the project directory and run the following command to install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Download Data:  Download the dataset from the provided URL.:
   - DNSE_Dataset_OHLC_daily.csv : https://drive.google.com/file/d/1EGi07cvhIIt-Wmdp2HH9u84XZcBouWJa/view?usp=sharing
4. Run Notebooks: Open each Jupyter Notebook individually and execute the code cells to perform the data preparation, model training, and backtesting analysis.
Note:

- This project uses Jupyter Notebooks which require a Python environment with relevant libraries installed. 
- Make sure you have Jupyter Notebook installed (`pip install jupyter`) to run the notebooks.

