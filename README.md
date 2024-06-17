
## The Optimisation of Data Centres using the MIT Supercloud Dataset🔋
My project focuses on enhancing energy efficiency in data centres using the MIT Supercloud Dataset. By developing an LSTM model, I aim to predict workload patterns and make informed decisions to reduce energy waste. This is crucial in an era where the cloud's carbon footprint is rapidly growing.

**This project was selected as a finalist at the Ada Lovelace Colloquium 2024**
![Project Poster](final%20poster%20submission%20(Double-Sided%20Poster%20(A3%20Landscape)).png)

## Key Highlights
- **Objective**: Develop an LSTM model for the MIT Supercloud Dataset to predict node usage patterns and improve energy efficiency.
- **Dataset**: Using a subsection of Node logs from the MIT Supercloud, capturing data every five minutes.
- **Methodology**: 
  - **Node Selection**: Focused on the top ten nodes with consistent data points.
  - **Sequence Creation**: Historical data from ten nodes used to predict one target node's future usage.
  - **Training**: Employed a bidirectional LSTM model with dropout layers to prevent overfitting.
- **Results**: 
  - The LSTM model accurately predicts load averages but struggles with sudden changes.
  - Best performance achieved with a smaller forecast horizon (5 minutes), showing lower MSE, MAE, and RMSE.

## Results Overview
- **Prediction Accuracy**: Model mirrors actual trends effectively for short-term predictions.
- **Performance Metrics**: Best results with a 5-minute forecast horizon.

## Author
- **Diana Ventura Valdivia**
- **Supervisor**: Professor Nirmalie Wiratunga
- **Institution**: RGU, BSc (Hons) Computer Science
