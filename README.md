# ESP32-CAM Web Stream (AI-Thinker)

This project is designed for the **AI-Thinker ESP32-CAM** module and provides a simple web-based camera stream over a **local Wi-Fi network**.

## Features

- Live MJPEG video stream from the camera
- Hosted directly on the ESP32-CAM
- Works entirely over local network (no cloud required)
- Automatically starts streaming after power-up

## Hardware Requirements

- AI-Thinker ESP32-CAM module  
- ESP32-CAM USB programming base (dedicated board with USB and reset circuitry)  
- USB cable for power and flashing  

## Usage

1. Flash the firmware to the ESP32-CAM using ESP-IDF or precompiled binary.
2. Power the device via USB.
3. Connect to the same local Wi-Fi network.
4. Access the video stream in a browser by visiting the ESP32-CAM IP address (e.g., `http://192.168.1.123`).

> No additional components are required – the system runs standalone on USB power only.

## License

MIT
