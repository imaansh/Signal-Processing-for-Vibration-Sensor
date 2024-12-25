# Signal-Processing-for-Vibration-Sensor
Processing vibration signals from a sensor using things speak and MATLAB
# Digital Signal Processing Project

A project implementing Digital Signal Processing (DSP) concepts using Arduino, MATLAB, and ThingSpeak for real-time data acquisition, processing, and analysis.

## 📜 Overview
This project demonstrates:
- Real-time sensor data acquisition using an **ESP8266 WiFi module** and **DHT11 sensor**.
- Cloud integration via **ThingSpeak** for data visualization and storage.
- DSP techniques for time-domain and frequency-domain analysis, along with statistical feature extraction using **MATLAB**.

## 🚀 Features
- **IoT Integration**: Use of ThingSpeak to store and visualize real-time sensor data.
- **Statistical Analysis**: Calculation of statistical features such as mean, variance, kurtosis, skewness, and RMS.
- **Signal Processing**: Insights into signal behavior in time and frequency domains.

## 🖥️ Technologies
- **Hardware**: ESP8266, DHT11 Sensor
- **Programming Languages**: C++ (Arduino), MATLAB
- **Tools**: Arduino IDE, ThingSpeak API, MATLAB

## 🛠️ Setup Instructions

### 1. Hardware Requirements
- ESP8266 WiFi module
- DHT11 sensor
- Analog sensor (optional)
- Internet connection

### 2. Software Requirements
- Arduino IDE
- MATLAB with ThingSpeak integration

### 3. Steps to Run

#### Configure Arduino Code:
1. Replace WiFi credentials in `ssid` and `pass`.
2. Update `myChannelNumber` and `myWriteAPIKey` with your ThingSpeak details.
3. Upload the code to your ESP8266 module.

#### Set Up ThingSpeak:
1. Create a ThingSpeak channel.
2. Note the channel ID and API keys for use in both Arduino and MATLAB code.

#### Analyze Data with MATLAB:
1. Replace `readChannelID` and `readAPIKey` in the MATLAB script with your ThingSpeak details.
2. Run the script to retrieve, clean, and analyze data.

---

## 📊 Results

### 1. Time-Domain Analysis:
Visualizes sensor data over time.

### 2. Frequency-Domain Analysis:
Analyzes frequency components of the signal.

### 3. Statistical Features:
- Mean, Maximum, Minimum, Range
- Variance, Kurtosis, Skewness, RMS

---

## 📈 Example Output

**Sample statistical analysis results:**
Mean: 45.32
Max: 78.21
Min: 12.45
Range: 65.76
Variance: 102.12
Kurtosis: 3.21
RMS: 50.15
Skewness: -0.67

