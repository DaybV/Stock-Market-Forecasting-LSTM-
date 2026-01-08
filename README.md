# Netflix Stock Price Prediction using LSTM Neural Networks
This project implements a Deep Learning architecture based on Long Short-Term Memory (LSTM) networks to forecast Netflix (NFLX) stock prices. By leveraging time-series analysis, the model captures complex temporal dependencies to predict future market trends.

📊 Business Overview
Predicting stock market movements is a critical challenge in financial engineering. This project moves beyond simple moving averages to implement a Deep Learning Pipeline that can assist in risk management and investment decision-making. By analyzing historical price patterns, the model provides a quantitative basis for identifying potential trend reversals and price targets.

🛠️ Tech Stack
Language: Python

Libraries: TensorFlow/Keras, Scikit-Learn, Pandas, NumPy, Matplotlib.
Data Ingestion: yfinance (Dynamic ELT Pipeline).
Model Architecture: Stacked LSTM (Multi-layer) with Dropout for regularization.
Data Strategy: Sequential Time-Series Splitting (70/15/15) shuffle=False to prevent data leakage.

📈 Performance Metrics & Results
The model’s accuracy was validated using unseen data from the test set, achieving high fidelity in trend following.

* MAE: 	3.09	On average, predictions are within $3.09 USD of the actual price.
* RMSE: 4.15	Indicates high model stability; penalizes larger deviations during volatility.

📝 Conclusion
This project demonstrates that LSTM networks are highly effective for financial time-series when combined with a rigorous engineering pipeline. By maintaining chronological order and optimizing the parameter space, we created a tool capable of predicting stock movements with a mean error of less than 3%.

📝 Conclusión
Este proyecto demuestra que las redes LSTM son altamente efectivas para series temporales financieras cuando se combinan con un pipeline de ingeniería riguroso. Al mantener el orden cronológico y optimizar el espacio de parámetros, creamos una herramienta capaz de predecir los movimientos de las acciones con un error medio de menos del 3%.

## 👩‍💻 Author
**Dayana B.**  
Industrial Engineer specialized in Data Science & AI  
Visual Analytics | BI | Python | Machine Learning |
[LinkedIn](https://www.linkedin.com/in/dayanabedoyavalestt)

---
