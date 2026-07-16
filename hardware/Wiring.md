# 🔌 Wiring Documentation

## Raspberry Pi Connections

| Connected Device | Interface |
|------------------|-----------|
| Camera Module | CSI Port |
| ESP32 | UART |
| Wi-Fi | Built-in |

---

## ESP32 Connections

| Connected Device | Interface |
|------------------|-----------|
| BTS7960 Motor Driver | GPIO |
| Ultrasonic Sensor | GPIO |
| IR Sensors | GPIO |
| Battery Voltage Sensor | ADC |
| Water Level Sensor | ADC |
| Water Pump Relay | GPIO |

---

## Power Distribution

24V Battery

↓

Battery Management System (BMS)

↓

DC-DC Buck Converter

↓

Raspberry Pi (5V)

↓

ESP32 (5V)

↓

Motor Driver

↓

Motors & Pump

---

## Communication

Raspberry Pi

⇅ UART

ESP32

---

> Final wiring diagram will be added after prototype development.
