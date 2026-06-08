# ESP32 IoT Projects

ESP32-based IoT and embedded projects exploring Wi-Fi, BLE, MQTT,
sensor integration, and AI API connectivity from embedded hardware.

---

## Projects

| Folder | Description | Protocols Used |
|---|---|---|
| 01_wifi_scan | Scan and list nearby Wi-Fi networks | Wi-Fi |
| 02_web_server | Host a live sensor dashboard from ESP32 | HTTP, Wi-Fi |
| 03_mqtt_sensor | Publish sensor data via MQTT broker | MQTT, Wi-Fi |
| 04_dht_logger | Log temperature and humidity over Wi-Fi | HTTP, Wi-Fi |
| 05_ble_scanner | BLE device scanner and RSSI reader | BLE |
| 06_esp_now_demo | Peer-to-peer communication between two ESP32s | ESP-NOW |
| 07_deep_sleep | Sensor read plus deep sleep power optimization | GPIO, ADC |
| 08_ai_api_call | Send sensor data to an AI REST API endpoint | HTTP, Wi-Fi |

---

## Hardware Used

- ESP32 DevKit v1
- DHT11 / DHT22 temperature-humidity sensor
- HC-SR04 ultrasonic sensor
- OLED display SSD1306 (optional)
- Relay module (optional)

---

## Skills Demonstrated

- ESP32 Wi-Fi station and AP modes
- BLE scanning and advertising (NimBLE)
- ESP-NOW peer-to-peer communication
- MQTT publish and subscribe
- HTTP client and web server on ESP32
- Deep sleep and wakeup timer configuration
- REST API calls from embedded hardware
- AI integration from microcontroller

---

## Platform

- Arduino IDE or PlatformIO
- Language: C++ (Arduino framework)
- Libraries: WiFi.h, HTTPClient.h, PubSubClient, NimBLE-Arduino, esp_sleep.h

---

## Getting Started

1. Open the project folder in Arduino IDE or PlatformIO
2. Install required libraries via Library Manager
3. Update Wi-Fi credentials in each sketch
4. Select ESP32 Dev Module as board
5. Upload and monitor at 115200 baud

---

## Connection to TankMate

Several techniques in these projects are used in the TankMate system:
- ESP-NOW peer communication (Motor Unit control)
- BLE NimBLE stack (mobile app interface)
- Wi-Fi HTTP client (Firebase upload)
- Deep sleep with timer wakeup (adaptive sleep cycle)
- REST API integration (AI prediction pipeline)

---

## Author

Kiran Gollapalli - Embedded Systems Developer
GitHub: @gollapallikiran2004-lab
