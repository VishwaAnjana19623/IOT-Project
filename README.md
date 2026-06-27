# IOT-Group Project
IoT-based smart fish tank water quality monitoring system with real-time analysis and automated mitigation alerts using an ESP32, Firebase, and Android.

# Smart Fish Tank Water Quality Monitor (IoT)
This project proposes an IoT-based Smart Fish Tank Water Quality Monitoring System that uses an ESP32 microcontroller and multiple sensors to measure important water parameters such as pH, temperature, turbidity, and Total Dissolved Solids (TDS). The system collects real-time data and sends it to a mobile application to ensure a healthy aquatic environment.

# Features
* Real-time water quality data collection using IoT sensors   
* Multi-parameter sensing (pH, Temperature, TDS, Turbidity)  
* Cloud-based data synchronization via Wi-Fi   
* Android mobile application for data visualization and analysis   
* Automated alert notifications if parameters exceed safe ranges  
# System Architecture
## Hardwear
* ESP32 Microcontroller  
* pH Sensor  
* TDS Sensor  
* Turbidity Sensor  
* DS18B20 Temperature Sensor
* 12V Power Pack with 5V Buck Converter

## Software
* ESP32 Firmware (C++/Arduino)
* Firebase Realtime Database   
* Android Mobile Application

## Data Pipeline
* ESP32 microcontroller collects continuous sensor readings   
* Data is transmitted through Wi-Fi to a Firebase Realtime Database   
* Android mobile app retrieves and synchronizes real-time sensor values   
* App analyzes values against safe ranges (e.g., pH 6.5-7.5, TDS 150-300 ppm, Temp 24-27°C)   
* Application generates alerts and suggests corrective actions for out-of-range parameters

## Business Model
* Primary Revenue: Sales of IoT monitoring devices
* Secondary Revenue: Mobile app premium features, subscriptions, and data storage services
* Additional: Bulk sales to fish farms, maintenance, and sensor replacement services

## Target Users
* Home aquarium owners
* Fish farmers (aquaculture industry)
* Aquarium shops
* Pet stores

## Impact
* Enables continuous water quality monitoring without manual testing   
* Promotes early detection of harmful conditions to prevent fish stress or death   
* Simplifies aquarium maintenance in a cost-effective and efficient manner

## Maintenance & Future Scope 
* Ensures measurement accuracy through proper, established sensor calibration curves  
* Long-term accuracy maintained through regular maintenance   
* Suitable for scaling into commercial small-scale fish farming applications

## Tech Stack
* Embedded Systems (ESP32)  
* Firebase Realtime Database   
* Android Development   
* C++ (Firmware)

## Authors
* Vishwa Anjana
* Thilanka dissanayake
* Savindu Lasal
* Sathsara Achintha


