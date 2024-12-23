# Stock-Price-Prediction-Using-LSTM-GRU-Ensemble-Model
This project leverages advanced deep learning techniques to predict stock prices using an ensemble model that integrates LSTM and GRU architectures. The model's performance was optimized with hyperparameter tuning using Optuna, achieving a Mean Squared Error (MSE) of 0.00028.

## Key Features
- **Data Acquisition**: Historical stock data is automatically fetched using the Yahoo Finance API.
- **Preprocessing**: Includes data cleaning, normalization, and preparation for training the deep learning models.
- **Ensemble Model**: Combines LSTM and GRU to leverage their strengths for better predictive accuracy.
- **Hyperparameter Tuning**: Utilizes Optuna to fine-tune model parameters and enhance performance.
- **Evaluation**: Achieved a Mean Squared Error (MSE) of 0.00028, showcasing robust predictive capabilities.

## Technologies Used
- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow/Keras
- **Hyperparameter Optimization**: Optuna
- **Data Acquisition**: Yahoo Finance API
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd stock-price-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook stock_price_predictor.ipynb
   ```
2. Select a stock ticker (e.g., `TSLA`) and specify the prediction time frame.
3. Execute the cells to preprocess data, train the model, and view predictions.

## Results
The model demonstrates reliable predictive performance, with an MSE of 0.00028. The ensemble approach outperforms individual LSTM and GRU models by effectively combining their strengths.

## Project Structure
- **`stock_price_predictor.ipynb`**: Main Jupyter Notebook containing the code and results.
- **`requirements.txt`**: List of dependencies for the project.
- **`data/`**: Directory for storing processed datasets.

## Future Enhancements
- Incorporating additional features such as market sentiment analysis.
- Extending the model to predict multiple stocks simultaneously.
- Deploying the model as a web-based application for broader accessibility.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to reach out with any questions or suggestions!
