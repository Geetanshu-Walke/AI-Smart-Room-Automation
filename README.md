AI-Based Smart Room Automation

An AI-powered room automation system using Computer Vision, IoT, and Embedded Systems.

Project Status: Ongoing 🚧

📌 Project Overview

This project aims to develop an intelligent room automation system that uses an existing CCTV camera to detect people, monitor room occupancy, and automate electrical appliances.

A computer processes CCTV footage using Python, OpenCV, and YOLO for person detection and occupancy tracking. An ESP32 handles sensor readings, physical button inputs, and appliance control.

The system will also provide PC and mobile dashboards for monitoring and manual control.

🎯 Project Objectives

- Detect people using CCTV and AI-based computer vision.
- Track people and estimate room occupancy.
- Monitor temperature and humidity.
- Automate lights, fans, and supported AC commands.
- Integrate ESP32 for hardware control.
- Provide automatic and manual operating modes.
- Maintain timestamp-based activity records.
- Develop PC and mobile monitoring dashboards.

⚙️ Proposed System Architecture

1. CCTV Camera

- Provides live video footage.
- Acts as the visual input source.

2. Computer / PC

- Python-based processing.
- OpenCV for video processing.
- YOLO for person detection.
- Object tracking and occupancy estimation.
- SQLite for storing activity records.

3. ESP32 Controller

- Reads temperature and humidity sensors.
- Handles physical button inputs.
- Controls connected outputs.
- Communicates with the computer through Wi-Fi.

4. Output and Monitoring

- Automatic light and fan control.
- Supported AC control interface.
- PC dashboard.
- Mobile web interface.

🧠 Proposed Automation Logic

- When a person is detected and occupancy is confirmed, the system requests lights and fans ON.
- When the room becomes empty, an occupancy timeout is applied before switching appliances OFF.
- When temperature exceeds 25°C, cooling is requested.
- When temperature falls to 24°C or below, the cooling request stops.
- Physical buttons allow manual operation.
- The system supports AUTO and MANUAL modes.

🛠️ Technologies & Tools

Technology| Application
Python| Main programming
OpenCV| Computer vision
YOLO| Person detection
Object Tracking| Occupancy estimation
ESP32| Hardware controller
DHT22 / SHT31| Temperature and humidity
MQTT / Wi-Fi| Communication
SQLite| Data storage
Flask| Dashboard backend
HTML, CSS, JavaScript| Web interface

🚀 Development Roadmap

1. CCTV live-feed integration.
2. AI-based person detection.
3. Person tracking and occupancy estimation.
4. Computer-to-ESP32 communication.
5. Temperature and humidity monitoring.
6. Physical button and output integration.
7. Database and dashboard development.
8. Mobile interface and complete system integration.

🔒 Safety & Privacy

- Initial hardware testing will use low-voltage DC loads.
- Household electrical appliances require properly rated and safely installed hardware.
- CCTV footage will be used only with appropriate permission.
- Manual operation should remain available during communication failures.

📊 Current Development Status

The project architecture and development plan have been prepared. Practical implementation is planned to begin shortly.

Code, circuit diagrams, hardware photographs, and testing results will be added as development progresses.

👨‍💻 Project Focus

Computer Vision | Artificial Intelligence | IoT | Electronics | Embedded Systems