# 🌦️ Timisoara Weather Data Analyzer

A Python project that retrieves weather data for Timisoara using the Open-Meteo API, processes the data with Pandas, visualizes temperature trends using Matplotlib, and exports the results to CSV files.

## 📌 Overview

This project demonstrates a complete data workflow:

1. Retrieve weather data from an external API.
2. Process JSON responses using Pandas.
3. Create visualizations using Matplotlib.
4. Export processed data to CSV files.
5. Organize generated data automatically.

The application collects weather information for Timisoara and generates a temperature analysis for the selected time period.

---

## 🛠 Technologies Used

### Python

Main programming language used for the project.

### Requests

Used to communicate with the Open-Meteo API and retrieve weather data.

### Pandas

Used for:

* Data cleaning
* Data processing
* DataFrame creation
* Data analysis

### Matplotlib

Used to create temperature visualizations and charts.

### Open-Meteo API

Weather data source used by the application.

### Git & GitHub

Used for version control and project management.

---

## 📊 Features

* Connects to a real-world weather API
* Retrieves weather forecast data for Timisoara
* Processes JSON API responses
* Creates structured Pandas DataFrames
* Generates temperature trend visualizations
* Saves charts as PNG files
* Exports weather data to CSV format
* Automatically creates a data folder if it does not exist

---

## 📂 Project Structure

```text
Timisoara-Weather-7days/
│
├── get_data.py
├── requirements.txt
├── README.md
├── weather_chart.png
│
└── data/
    └── Timisoara_weather.csv
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/gayadamohammad-coder/Timisoara-Weather-7days.git
```

Move into the project folder:

```bash
cd Timisoara-Weather-7days
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run:

```bash
python get_data.py
```

The application will:

* Request weather data from Open-Meteo
* Process the returned JSON data
* Generate a weather chart
* Save the chart as `weather_chart.png`
* Export the data to `data/Timisoara_weather.csv`

---

## 📈 Skills Demonstrated

This project demonstrates:

* API Integration
* Data Analysis
* Data Visualization
* Working with JSON Data
* CSV Export
* File Management
* Python Programming
* Git Version Control

---

## 🎯 Future Improvements

* Compare weather data across multiple cities
* Add humidity and precipitation analysis
* Create interactive dashboards with Streamlit
* Add machine learning forecasting
* Build an AI-powered weather assistant

---

## Author

Mohammad Gayada

Artificial Intelligence Student | Python Developer | Future AI Engineer
