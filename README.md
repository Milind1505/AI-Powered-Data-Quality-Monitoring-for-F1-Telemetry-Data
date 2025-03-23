# AI-Powered-Data-Quality-Monitoring-for-F1-Telemetry-Data

## Project Overview

This project demonstrates an AI-powered pipeline to monitor and flag anomalies in Formula 1 telemetry data for driver George Russell. It utilizes the `fastf1` library to access telemetry data, builds a rules engine, and employs various anomaly detection models, including Isolation Forest, Local Outlier Factor (LOF), One-Class SVM (OCSVM), and autoencoders. The results are visualized with Plotly for both static and interactive exploration, providing insights into potential data quality issues.

## Data Source

The project uses the `fastf1` library to access Formula 1 telemetry data for George Russell in the 2023 Bahrain Grand Prix.

## Methodology

1. **Data Loading and Preprocessing:** Load and prepare the telemetry data, selecting relevant features and splitting it into training and testing sets.
2. **Rules Engine:** Implement a rules engine to flag basic anomalies based on predefined thresholds.
3. **Anomaly Detection Models:** Train and apply Isolation Forest, LOF, OCSVM, and autoencoder models to detect anomalies.
4. **Visualization with Plotly:** Create static and interactive visualizations to explore the results and identify potential anomalies.

## Findings and Conclusions

- Summarize the key findings from the analysis of each anomaly detection model.
- Discuss the overall conclusions about the effectiveness of the pipeline in identifying anomalies.

## Potential Applications and Extensions

- Real-time Anomaly Detection
- Predictive Maintenance
- Driver Performance Analysis
- Data Quality Monitoring in Other Domains

## Limitations

- Acknowledge any limitations of the project, such as the need for parameter tuning or potential for missing subtle anomalies.

## Getting Started

1. Clone the repository: `git clone <repository_url>`
2. Install the required libraries: `pip install -r requirements.txt` (create a `requirements.txt` file listing the libraries)
3. Run the Jupyter Notebook: `jupyter notebook F1_Anomaly_Detection.ipynb` (replace with your notebook filename)

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

Specify the license under which your project is distributed (e.g., MIT License).
