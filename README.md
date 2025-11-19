
# Cardio Pulse PRO

**Cardio Pulse PRO** is a heart rate (HR) and heart rate variability (HRV) monitoring device built with a Raspberry Pi Pico W and a Crowtail PPG pulse sensor. It detects peaks from a live PPG signal, calculates HR and HRV metrics locally, and sends interval data to Kubios Cloud for advanced analysis. The device includes an OLED display and rotary encoder for simple navigation, and shows both real-time and historical measurements.

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

## Components

1. **Raspberry Pi Pico W**
2. **Crowtail Pulse Sensor v2.0**
3. **SSD1306 OLED Display**
4. **Rotary Encoder**
5. **Protoboard with Grove Connectors**
6. **USB-C Cable**

---

## Getting Started

### Prerequisites

- [Thonny IDE](https://thonny.org)
- MicroPython Firmware for Raspberry Pi Pico W

### Setup

1. **Assemble Hardware**:
   - Connect the OLED display and pulse sensor to the Raspberry Pi Pico W using Grove connectors.
   - Connect the device to a power source via USB.

2. **Install Software**:
   - Load the MicroPython firmware onto the Raspberry Pi Pico W.
   - Clone or download the repository.

3. **Configure Wi-Fi**:
   - Edit the `connect_to_wlan.py` file to include your Wi-Fi credentials.
   - Run the script to connect the device to your network.

4. **Run the Application**:
   - Open the main program in Thonny and execute it on the connected Raspberry Pi Pico W.

---

## Documentation

- [User Manual](./User_Manual.pdf)
- [Project Report](./Project_Report.pdf)

---

## Contributors

- **Ade Aiho**
- **Topias Aho**
- **Jonne Roponen**
