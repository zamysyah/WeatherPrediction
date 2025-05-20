```markdown
# Weather Prediction Model Comparison

This project presents a comparative analysis of three machine learning models—Random Forest, Support Vector Regression (SVR), and XGBoost—for predicting weather conditions based on historical data.

## 📌 Project Objectives

- Predict future weather variables such as air temperature using historical weather data.
- Compare the performance of three regression models: Random Forest, SVR, and XGBoost.
- Evaluate model performance using common regression metrics: MAE, RMSE, and R² Score.

## 🧪 Models Used

- **Random Forest Regressor**
- **Support Vector Regression (SVR)**
- **XGBoost Regressor**

## 📊 Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score (Coefficient of Determination)**

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn (for visualization)

## 📁 Project Structure

```

├── data/
│   └── weather\_data.csv         # Historical weather dataset
├── notebooks/
│   └── model\_comparison.ipynb   # Jupyter Notebook for training & evaluation
├── results/
│   └── performance\_metrics.csv  # Performance results of the models
├── README.md
└── requirements.txt

````

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-model-comparison.git
   cd weather-model-comparison
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/model_comparison.ipynb
   ```

## 📈 Example Results

| Model         | MAE  | MSE | R² Score |
| ------------- | ---- | ---- | -------- |
| Random Forest | 0.362433 | 0.189044 | 0.763657     |
| SVR           | 0.619069 | 0.571662 | 0.285307     |
| XGBoost       | 0.288794 | 0.132395 | 0.834479     |

*(Note: These are example results. Actual performance may vary depending on the dataset.)*

## 📌 Future Work

* Extend prediction horizon (e.g., 2–5 years ahead)
* Include more weather variables (humidity, wind speed, etc.)
* Integrate LSTM for time-series based deep learning comparison

## 📜 License

This project is licensed under the MIT License.

## 🤝 Acknowledgements

Thanks to BMKG or any other source for providing the historical weather data used in this project.

```

