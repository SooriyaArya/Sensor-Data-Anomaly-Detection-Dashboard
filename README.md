Sensor Data Anomaly Detection Dashboard
This repository features an interactive web application built using Dash and Plotly, designed to analyze sensor data and identify anomalies through machine learning techniques. The dashboard utilizes the Isolation Forest algorithm to detect anomalous readings from synthetic sensor data, and offers various visualizations to help users explore patterns, relationships, and outliers in the data.

Features
Synthetic Sensor Data Generation: Randomly generated sensor data, with added anomalies for anomaly detection demonstration.
Machine Learning for Anomaly Detection: Uses the Isolation Forest algorithm to compute anomaly scores and classify data points as "Normal" or "Anomaly."
Interactive Visualizations:
Correlation heatmap of sensor readings.
Pair plots for visualizing relationships between multiple sensor readings.
Box plots and violin plots for analyzing data distributions.
Anomaly score distribution to explore how anomalies are spread in the dataset.
Swarm plots and count plots to differentiate between normal and anomalous readings.
Sensor heatmaps to track sensor data behavior over time.
Dash-Powered Web Interface: A dynamic and interactive web application to visually explore the data in real-time.
Project Structure
bash
Copy code
.
├── app.py                 # Main Dash application
├── requirements.txt       # Required Python libraries for the project
├── README.md              # Project description and details
└── data                   # (Optional) Folder for storing or importing real-world sensor data
Installation
Clone the repository:
bash
Copy code
Create a virtual environment (optional but recommended):
bash
Copy code
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies: Install the required Python packages using pip:
bash
Copy code
pip install -r requirements.txt
Usage
Run the Dash application:
bash
Copy code
python app.py
Access the dashboard: Open your web browser and navigate to http://127.0.0.1:8007/ to access the sensor data anomaly detection dashboard.
Visualizations
The dashboard includes the following visualizations:
Correlation Heatmap: Visualizes the correlation between different sensor readings.
Pair Plot: Shows relationships between pairs of sensor readings, colored by anomaly labels.
Box Plot: Displays the distribution of sensor readings by label.
Anomaly Scores Distribution: Shows how anomaly scores are distributed across normal and anomalous data points.
Violin Plot: Illustrates the density of sensor readings for normal and anomalous data.
Count Plot: Counts and compares the number of normal vs. anomalous readings.
Swarm Plot: Shows sensor readings scattered by label, indicating clusters and outliers.
Sensor Heatmap: A time-series heatmap of sensor readings for tracking trends over time.
Technologies Used
Dash: A Python framework for building web applications.
Plotly: For interactive, high-quality visualizations.
Pandas & NumPy: For data manipulation and analysis.
Scikit-Learn: For applying machine learning techniques (Isolation Forest) to detect anomalies.
Python: The primary programming language for this project.
License
This project is licensed under the MIT License - see the LICENSE file for details.

