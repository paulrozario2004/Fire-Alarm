# 🔥 Fire Alarm System using Arduino, Gas Sensor, and Flame Sensor

This project is a basic yet powerful **fire detection and alert system** developed using an **Arduino Uno**, an **MQ-2 gas sensor**, and an **IR flame sensor**. It monitors the surrounding environment for flammable gases and visible flames, and triggers an alert using a buzzer when danger is detected.

---

## 📷 Project Overview

The system is designed to:
- **Detect gas leaks** using the MQ-2 sensor (e.g., smoke, LPG, methane)
- **Detect open flames** using an IR-based flame sensor
- **Trigger an alarm** (via buzzer) when either hazard is detected
- Provide **serial monitor output** for real-time readings and debugging

---

## 🧰 Components Used

| Component        | Quantity |
|------------------|----------|
| Arduino Uno      | 1        |
| MQ-2 Gas Sensor  | 1        |
| IR Flame Sensor  | 1        |
| Buzzer           | 1        |
| Jumper Wires     | As needed |
| Breadboard       | 1        |
| USB Cable        | 1        |
| (Optional) LED or LCD Display | 1    |

---

## 🔌 Circuit Connections

| Arduino Pin | Component         | Description             |
|-------------|------------------|-------------------------|
| A0          | MQ-2 Analog Out  | Gas sensor input        |
| D2          | Flame Sensor OUT | Flame detection input   |
| D8          | Buzzer (+)       | Buzzer output           |
| GND, 5V     | All sensors      | Power supply            |

---

## 🧪 How to Test

1. Power the Arduino through USB or an external battery.
2. Open the Serial Monitor to observe real-time gas and flame data.
3. Use a lighter (without lighting it) near the flame sensor to simulate a flame.
4. Release a small amount of gas or smoke near the gas sensor (in a ventilated area).
5. When fire or gas is detected, the buzzer will sound.

---

## 🚀 Future Enhancements

- Add SMS alert capability using a GSM module (e.g., SIM800L)
- Add internet connectivity using ESP8266/ESP32 for remote alerts
- Connect a relay module to control electrical appliances
- Cloud integration (ThingSpeak, Firebase) for real-time monitoring
- Battery backup using Li-ion or 9V rechargeable battery pack

