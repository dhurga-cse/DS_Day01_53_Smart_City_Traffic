# DS_Day01_53 — Smart City Traffic Congestion Analysis

## Project Overview

This project analyzes traffic data to identify congestion hotspots, peak traffic periods, and traffic patterns in a smart city environment.

A Random Forest machine learning model is used to classify observations as normal or high congestion.

## Dataset

The dataset contains traffic sensor and weather information.

Main fields:

- Timestamp
- Junction_ID
- Vehicle_Count
- Average_Speed
- Road_Occupancy
- Signal_Status
- Weather
- Event_Status

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Analysis

The project includes:

- Data cleaning and validation
- Descriptive statistics
- Traffic analysis by junction
- Traffic analysis by hour
- Congestion hotspot detection
- Event vs normal traffic comparison
- Congestion heatmap
- Random Forest classification
- Model evaluation
- Feature importance analysis

## Machine Learning

### Algorithm

Random Forest Classifier

### Target

- `0` → Normal congestion
- `1` → High congestion

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Practical Applications

The analysis can support:

- Traffic monitoring
- Congestion hotspot identification
- Traffic signal planning
- Route management
- Event-day traffic planning

## Limitations

The dataset contains only 50 traffic observations.

Some fields such as Average_Speed, Road_Occupancy, Signal_Status, and Event_Status were derived or simulated because they were not directly available in the original source dataset.

Therefore, the results should not be treated as city-wide real-world conclusions.

## Future Improvements

- Use real-time traffic sensor data
- Collect data for multiple months
- Add real speed and road occupancy measurements
- Improve congestion propagation analysis
- Build an interactive traffic dashboard
- Deploy the Random Forest model as an API
