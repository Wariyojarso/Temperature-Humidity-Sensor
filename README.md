# Temperature-Humidity-Sensor


This project uses an **Arduino Mega 2560 R3**, **DHT11 sensor**, and an **LCD 1602A** to measure and display temperature & humidity.

## Components Used
- Mega 2560 R3
- DHT11 Sensor
- LCD 1602A (with pin header)
- Potentiometer
- Breadboard & Jumper Wires

## Wiring Instructions
| Component | Pin | Arduino Mega 2560 |
|-----------|----|------------------|
| **DHT11** | VCC | 5V |
|  | Data | Pin 2 |
|  | GND | GND |
| **LCD 1602A** | VSS | GND |
|  | VDD | 5V |
|  | RS | Pin 7 |
|  | E | Pin 8 |
|  | D4-D7 | Pins 9-12 |
| **Potentiometer** | VCC | 5V |
|  | GND | GND |
|  | Middle | LCD V0 |

## Uploading the Code
1. Open **Arduino IDE**.
2. Install the **DHT** and **LiquidCrystal** libraries (`Sketch > Include Library > Manage Libraries`).
3. Upload the `temperature_humidity_sensor.ino` file to your **Mega 2560**.
youtube video link https://youtu.be/LFQMO0YLEUY
