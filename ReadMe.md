# ESPilot32 V1

An open-source, heavy-duty, ESP32-powered flight controller designed for ultimate airframe versatility. By leveraging the dual-core processing power and built-in wireless capabilities of the ESP32, this board serves as a robust, all-in-one command center for quadcopters, fixed-wing planes, VTOLs, and custom scratch-built aircraft.

Unlike micro-scale racing boards, the ESPilot32 prioritizes structural durability, massive I/O accessibility, and reliable power regulation to handle complex, multi-role UAV projects.

---

## Key Features

* **Dual-Core Architecture:** Dedicated core for high-frequency PID loops and sensor fusion, leaving the second core free for telemetry and wireless communication.
* **Universal Airframe Support:** Configurable mixer maps for multirotors, traditional airplanes, flying wings, and VTOL transition aircraft.
* **Built-in Wireless Telemetry:** Native Wi-Fi and Bluetooth support for real-time, cable-free configuration and over-the-air (OTA) updates.
* **Robust Power Distribution:** Heavy-duty onboard voltage regulation designed to handle high current spikes and supply clean power to servos and peripherals.
* **Expanded I/O:** Fully exposed pinouts for hardware UARTs, I2C, SPI, and PWM outputs to easily interface with GPS, compasses, lidars, and extra servos.

---

## Hardware Specifications

| Component | Specification |
| :--- | :--- |
| **MCU** | ESP32-WROOM-32 (Dual-Core 32-bit Xtensa LX6 @ 240MHz) |
| **IMU** | [e.g., MPU6050 / ICM-42688-P] |
| **Barometer** | [e.g., BMP280 / MS5611] (For precise altitude hold) |
| **Input Voltage** | [e.g., 2S - 6S LiPo LiPo Input] |
| **Output Voltage** | [5V @ 8A && 12V @ 8A && 3V3 @ 5A] |
| **Flash Memory** | 4MB / 8MB (For blackbox data logging) |

---

## 📂 Repository Structure

* `/firmware` - Core flight control code, sensor drivers, and PID loop logic.
* `/hardware` - KiCAD/Eagle schematic files, PCB layouts, and Bill of Materials (BOM).
* `/enclosure` - STL/3D printing files for the protective hardware case.
* `/docs` - Pinout diagrams, wiring guides, and configuration manuals.

---

## 🛠️ Getting Started
Look at the "Getting_Started.md" file to get started!
