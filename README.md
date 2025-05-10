# DS18B20 Temperature Sensor Project

This project demonstrates how to interface a **DS18B20 digital temperature sensor** with an ESP32. The circuit and code were created using the Wokwi online simulator.

## 🧰 Components

- ESP32
- DS18B20 Temperature Sensor
- 4.7kΩ Resistor (pull-up)
- Jumper wires
- Breadboard

## 🔗 Simulation Link

Run the project in Wokwi:  
https://wokwi.com/projects/430583620731284481

## 🚀 Getting Started

1. Open `sketch.ino` in the Arduino IDE.
2. Install the required libraries listed in `libraries.txt`:
   - OneWire
   - DallasTemperature
3. Upload the code to your ESP32.
4. Open Serial Monitor to view temperature readings.

## 🖼 Diagram

The `diagram.json` file contains the Wokwi visual layout.

## 📝 Notes

Ensure you use a pull-up resistor (4.7kΩ) between the sensor's data line and VCC.
