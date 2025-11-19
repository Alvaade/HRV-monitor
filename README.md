
# Cardio Pulse PRO

**Cardio Pulse PRO** is a heart rate (HR) and heart rate variability (HRV) monitoring device designed for stress and recovery analysis. The device is built with a Raspberry Pi Pico W and a Crowtail PPG pulse sensor. It detects peaks from a live PPG signal, calculates HR and HRV metrics locally, and sends interval data to Kubios Cloud for advanced analysis. The device includes an OLED display and rotary encoder for simple navigation, and shows both real-time and historical measurements.

---

## Features

- Real-time heart rate measurement
- Local HRV analysis
- Kubios Cloud integration for advanced HRV metrics
- Live PPG waveform drawing on OLED screen
- Measurement history stored locally on the Pico
- Menu navigation with a rotary encoder
- LED peak indicator for visual feedback

---

## Technical Specifications

- **Microcontroller**: Raspberry Pi Pico W
- **Heart Rate Sensor**: Crowtail Pulse Sensor v2.0
- **Display**: SSD1306-compatible OLED (128x64 pixels)
- **Interface**: Rotary encoder with push-button
- **Connectivity**: Wi-Fi
- **Language**: MicroPython

---

## Documentation

- [User Manual](./User_Manual.pdf)
- [Project Report](./Project_Report.pdf)

---

## Contributors

- **Ade Aiho**
- **Topias Aho**
- **Jonne Roponen**
