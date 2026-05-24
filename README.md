# weather-reporting-iot-esp32
An IoT-based smart weather monitoring system built using ESP32, DHT11 sensor, Rain Sensor, and Supabase cloud integration for real-time environmental monitoring and data analytics. The system continuously collects temperature, humidity, and rainfall data and uploads it to the cloud for remote access and visualization.

---

## Features

- Real-time temperature monitoring
- Humidity monitoring using DHT11 sensor
- Rainfall detection using Rain Sensor
- Cloud integration with Supabase
- Wi-Fi-enabled IoT communication
- Real-time dashboard updates
- Historical weather data storage
- Lightweight and cost-effective system
- Remote monitoring from internet-connected devices

---

## Project Objective

The objective of this project is to develop a low-cost and efficient IoT-based weather reporting system capable of collecting, transmitting, storing, and displaying environmental data in real time using ESP32 and cloud technologies.

The system focuses on:
- Real-time data acquisition
- Wireless cloud communication
- Remote accessibility
- Cloud database integration
- Reliable and scalable monitoring

---

## Tech Stack

### Hardware Components
- ESP32 Dev Module
- DHT11 Temperature & Humidity Sensor
- Rain Sensor Module
- Breadboard
- Jumper Wires
- USB Data Cable

### Software & Technologies
- Arduino IDE
- Embedded C/C++
- WiFi Library
- HTTPClient Library
- ArduinoJson Library
- DHT Sensor Library
- Supabase Cloud Database
- REST API

---

## System Architecture

The system works as follows:

1. Sensors collect environmental data
2. ESP32 processes the sensor readings
3. ESP32 connects to Wi-Fi
4. Data is converted into JSON format
5. HTTP POST requests send data to Supabase
6. Data is stored in the cloud database
7. Dashboard displays real-time weather information

---


## Software Implementation

The ESP32 is programmed using Arduino IDE. The microcontroller continuously:
- Reads temperature and humidity values from DHT11
- Detects rainfall status using rain sensor
- Processes sensor data
- Sends readings to Supabase using HTTP requests

JSON formatting and REST APIs are used for efficient cloud communication.

---

## Cloud Integration

The system uses Supabase as a real-time cloud database.

### Functionalities
- Real-time data storage
- Historical data retrieval
- Structured database tables
- Remote accessibility
- Data analytics support

Sensor readings are sent through HTTP POST requests in JSON format using Wi-Fi connectivity.

---

## Sample Data

| Date | Time | Temperature | Humidity | Rain Status |
|---|---|---|---|---|
| 20-04-2026 | 10:05 AM | 27.0°C | 41.2% | Yes |
| 20-04-2026 | 01:12 PM | 26.0°C | 41.3% | Yes |
| 21-04-2026 | 09:44 AM | 27.2°C | 40.3% | No |

---

## Results

- Accurate real-time monitoring achieved
- Stable Wi-Fi communication with minimal delay
- Successful cloud storage using Supabase
- Reliable rainfall detection
- Continuous operation with low power consumption
- Automatic dashboard updates

The project successfully demonstrated real-time environmental monitoring using IoT and cloud technologies.

---

## Future Improvements

Possible future enhancements include:
- Air Quality Monitoring
- Wind Speed Detection
- Mobile Application Integration
- Alert & Notification System
- Machine Learning-based Weather Prediction
- Advanced Data Visualization Dashboard
- Predictive Analytics

---

## Applications

- Smart Agriculture
- Home Weather Monitoring
- Environmental Research
- Educational IoT Projects
- Small Weather Stations
- Smart City Systems

---

## Repository Structure

```text
weather-reporting-iot-esp32/
│
├── code/
│   └── weather_monitoring.ino
│
├── images/
│   ├── circuit-diagram.png
│   ├── dashboard.png
│   ├── serial-monitor.png
│   └── block-diagram.png
│
├── docs/
│   └── project-report.pdf
│
├── README.md
└── requirements.txt
```

---

## Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/kinjal-019/weather-reporting-iot-esp32.git
```

### 2. Open Arduino IDE

Install required libraries:
- WiFi
- HTTPClient
- ArduinoJson
- DHT Sensor Library

### 3. Connect ESP32

Connect:
- DHT11 Sensor
- Rain Sensor
- Breadboard wiring

### 4. Upload Code

Upload `.ino` file to ESP32 using Arduino IDE.

### 5. Configure Wi-Fi & Supabase

Update:
- Wi-Fi SSID
- Password
- Supabase URL
- API Key

inside the Arduino code.

---

## Author
- Kinjal S. Chandel
---

## License

This project is developed for educational and academic purposes.
