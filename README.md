# Global Weather Forecasting System & Climate Analysis Platform

## 🌍 Overview
This project is a **Global Weather Forecasting System and Climate Analysis Platform** that utilizes **AWS cloud services** and **IoT-based monitoring systems** to collect and analyze real-time weather data. The system is designed to provide accurate location-based forecasts and climate insights, particularly for Andhra Pradesh.

## 🚀 Features
- **Real-Time Weather Data Collection**: Utilizes IoT devices with **Arduino Nano, ESP32, and sensors** to gather weather parameters.
- **AWS Cloud Integration**:
  - **EC2** for computation
  - **RDS** for database management
  - **S3** for data storage
  - **Lambda** for serverless processing
- **Geospatial Data Processing**: Implements **PostgreSQL and PostGIS** for accurate location-based climate forecasts.
- **Machine Learning Models**: Used for climate trend analysis and forecasting.
- **Data Visualization**: Interactive dashboards and charts for climate insights.

## 🛠️ Technologies Used
- **AWS (EC2, RDS, Lambda, S3)**
- **Arduino Nano & ESP32**
- **PostgreSQL & PostGIS**
- **Python & Machine Learning Models**
- **Data Visualization Tools**

## 🔧 Installation
### Prerequisites
Ensure you have **Python 3.x**, **PostgreSQL**, and necessary AWS credentials configured.

### Steps to Install
```sh
# Clone the repository
git clone https://github.com/your-username/weather-forecasting-platform.git
cd weather-forecasting-platform

# Install dependencies
pip install -r requirements.txt
```

## 🚀 Usage
1. **Deploy IoT Sensors**: Set up **Arduino Nano, ESP32, and sensors** for real-time data collection.
2. **Run the Data Ingestion Pipeline**:
   ```sh
   python data_ingestion.py
   ```
3. **Process and Analyze Weather Data**:
   ```sh
   python climate_analysis.py
   ```
4. **Visualize Climate Insights**: Access interactive dashboards for real-time climate data.

## 🌦️ Data Processing & Storage
- Weather data is collected from IoT sensors and stored in **AWS RDS (PostgreSQL)**.
- **PostGIS** is used for geospatial data processing.
- **AWS Lambda** processes real-time data streams.

## 📊 Machine Learning & Visualization
- Implemented **ML models** for climate forecasting.
- Created **visualization dashboards** for data representation.

## 📌 Challenges Faced
- **Real-Time Data Collection**: Ensured continuous and error-free data flow from IoT sensors.
- **Scalability on AWS**: Optimized services to handle large-scale climate data efficiently.
- **Geospatial Data Processing**: Utilized **PostGIS** for accurate regional forecasting.

## 👨‍💻 Author
**Karthikeyan**  
