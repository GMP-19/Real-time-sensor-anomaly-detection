# Real-Time Sensor Anomaly Detection and Monitoring System

## Overview

This project explores unsupervised anomaly detection for sensor data using the **Isolation Forest** algorithm. It uses the NASA C-MAPSS FD001 dataset to identify unusual sensor observations and investigate their behavior through data analysis and monitoring simulations.

The goal is to demonstrate how machine learning can support sensor monitoring by highlighting observations that differ from typical operating patterns.

## Objectives

- Analyze sensor data from the NASA C-MAPSS FD001 dataset.
- Select and analyze 15 variable sensor features.
- Apply Isolation Forest for unsupervised anomaly detection.
- Evaluate how model settings affect anomaly detection results.
- Investigate detected anomalies, including observations associated with engine 5.
- Simulate sequential monitoring of sensor observations.

## Dataset

- **Dataset:** NASA C-MAPSS FD001
- **Observations:** 20,631
- **Engines:** 100
- **Selected variable sensor features:** 15

The dataset contains engine operating and sensor measurements used to study patterns and identify unusual observations.

## Methodology

1. **Data preparation:** Load and inspect the sensor dataset and select variable sensor features.
2. **Feature selection:** Use 15 variable sensor features for the anomaly detection analysis.
3. **Modeling:** Apply the Isolation Forest algorithm to identify unusual observations without requiring labeled anomaly examples.
4. **Sensitivity analysis:** Compare detection behavior under different contamination and estimator settings.
5. **Anomaly investigation:** Examine detected observations and analyze engine 5.
6. **Monitoring simulation:** Simulate sequential processing of observations to explore a real-time monitoring workflow.

## Results

The current analysis identified:

- **1,032 detected anomalies**
- **5.0% anomaly rate**
- **15 selected sensor features**
- Sensitivity analysis across different model settings
- An investigation of detected anomalies associated with engine 5
- A sequential monitoring simulation

These anomalies are model-detected unusual observations; they should not automatically be interpreted as confirmed mechanical failures.

## Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

## How to Run

1. Open the notebook in this repository.
2. Select **Open in Colab** if the notebook is stored on GitHub and you want to run it in Google Colab.
3. Upload or configure access to the NASA C-MAPSS FD001 dataset as required by the notebook.
4. Run the notebook cells in order.

Check the notebook for the exact dataset path and any additional dependencies.

## Future Improvements

- Add interactive visualizations for sensor monitoring.
- Evaluate detection performance against suitable labeled data, where available.
- Develop a streaming pipeline for incoming sensor observations.
- Explore alerting and dashboard integration.

## Author

**Praveen Kumar Gopinath**

GitHub: [GMP-19](https://github.com/GMP-19)

Portfolio: [gmpcognition.com](https://gmpcognition.com)

---

*This project is an exploration of machine-learning-based sensor anomaly detection and sequential monitoring using the NASA C-MAPSS FD001 dataset.*
