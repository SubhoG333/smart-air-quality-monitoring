# Smart Air Quality Monitoring System 🚨🌿

This is an IoT-based project that uses ESP32, MQ135, and DHT22 sensors to monitor air quality in real time and sends alerts via Telegram bot when pollution levels exceed a certain threshold.

## 🔧 Components Used

- ESP32 Development Board
- MQ135 Gas Sensor
- DHT22 Temperature & Humidity Sensor
- Jumper Wires
- Breadboard
- Internet connection (Wi-Fi)
- Telegram Bot

## 🧠 Project Overview

- Collects real-time air quality data (CO2, NH3, etc.) using MQ135.
- Monitors temperature and humidity using DHT22.
- Sends alert messages to a predefined Telegram chat using a bot.
- Can be expanded to include mobile dashboards (Blynk, etc.)

## 🖼️ Circuit Diagram

> *(Insert a photo or link to your Fritzing or hand-drawn circuit diagram)*

## 💻 Code Overview

The Arduino sketch:
- Initializes Wi-Fi and Telegram bot
- Reads sensor values every few seconds
- Sends message if values exceed set limit

## 🧪 How to Use

1. Set up the circuit.
2. Connect ESP32 to Arduino IDE.
3. Upload the code (`smart_air_monitor.ino`).
4. Configure your Telegram bot token and chat ID.
5. Open Serial Monitor and watch live readings.

## 📦 Dependencies

- ArduinoJson
- UniversalTelegramBot
- WiFiClientSecure

## 📸 Screenshots
https://github.com/SubhoG333/smart-air-quality-monitoring/blob/main/App_Interface.jpg
https://github.com/SubhoG333/smart-air-quality-monitoring/blob/main/Full_Connections.jpg
https://github.com/SubhoG333/smart-air-quality-monitoring/blob/main/Full_Setup.jpg
https://github.com/SubhoG333/smart-air-quality-monitoring/blob/main/Web_interface.jpg

## 🚀 Future Improvements

- Add OLED display
- Store data in cloud or Firebase
- Mobile app integration

## 🤝 Author

**Subhajit Ghosh**  
B.Tech in Computer Science & Design  
[LinkedIn](https://www.linkedin.com/in/subhajitghosh) | [GitHub](https://github.com/subhajitghosh)

