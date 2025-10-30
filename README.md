# Smart Irrigation System with LoRa and Machine Learning

## Project Overview
This project is a Smart Irrigation System that leverages sensor data and embedded machine learning to automate irrigation pump operation efficiently. It uses LoRa wireless communication for long-range data transmission and a Random Forest Classifier deployed on Arduino for local decision making.

## Features
- Real-time sensor monitoring: temperature, humidity, soil moisture, water level, and water flow
- Machine Learning inference running on Arduino using EloquentTinyML
- LoRa-based wireless communication between irrigation field and receiver base station
- Automatic pump control based on ML prediction to conserve water usage

## Technologies
- Arduino Uno
- LoRa SX1278 modules
- DHT11, soil moisture sensor, water level sensor, YF-S201 flow sensor
- Random Forest Classifier (embedded ML model)
- Arduino IDE, C++
- Python (for initial ML model training)

## Installation
1. Connect sensors and relay to Arduino as per wiring diagram.
2. Install required Arduino libraries: DHT, LoRa, EloquentTinyML.
3. Upload sender and receiver Arduino codes to respective hardware.
4. Ensure LoRa modules are configured at 433 MHz.
5. Power devices and monitor sensor readings in Serial Monitor.

## Usage
- The system will monitor environmental parameters and decide irrigation needs.
- Pump status and sensor data are transmitted to the receiver node via LoRa.
- Users can monitor real-time data on the receiver Arduino Serial Monitor.

## Results
The system automates irrigation efficiently, reducing water waste and manual intervention. The ML model achieved high accuracy (100%) on test data, validating the approach.

## Future Work
- Dynamic allocation from multiple water sources.
- Integration of weather forecasting for predictive irrigation.
- Scalability for larger agricultural deployments.

## Author

**Sampath Magapu**  
Email: [sampathmagapu11@gmail.com](mailto:sampathmagapu11@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/sampath-magapu-9b5102253/](https://www.linkedin.com/in/sampath-magapu-9b5102253/)

## License
This project is licensed under the MIT License - see the LICENSE file for details.
