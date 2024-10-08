# IoT-Based Irrigation System

## Overview
The **IoT-Based Irrigation System** is an innovative solution designed to improve water management in agricultural fields. It uses real-time sensor data, cloud computing, and embedded systems to automate irrigation and optimize water use. The system provides remote monitoring and control through a cloud interface, ensuring efficient irrigation and resource management.

## Key Features
- **Real-time Monitoring:**
  - Collects data from soil moisture, temperature, and humidity sensors.
  - Sends data to the cloud for real-time analysis and monitoring.
  
- **Automated Irrigation:**
  - Automatically triggers irrigation based on soil moisture and environmental conditions.
  - Users can also control irrigation remotely via a cloud-based dashboard.
  
- **Cloud Integration:**
  - Cloud infrastructure stores sensor data and provides analytics.
  - MQTT protocol is used for real-time data transfer, allowing remote control and monitoring.
  
- **C++-Powered Embedded System:**
  - Core logic is written in C++, running on an Arduino microcontroller.
  - Handles sensor data collection, decision-making, and control of irrigation valves.
  
## Project Structure

![Screenshot 2024-09-16 185221](https://github.com/user-attachments/assets/1e5d3f4d-8bb4-4549-af1b-8108a32f846f)

![Screenshot 2024-02-14 223422](https://github.com/user-attachments/assets/c247baa3-ca2c-4c07-9c15-4b1969877283)
### Cloud Integration
- The cloud platform enables real-time monitoring of sensor data and remote control of the irrigation system.
- Data is transmitted via the MQTT protocol, ensuring efficient communication between sensors, the microcontroller, and the cloud dashboard.
- Historical data is stored in the cloud for analysis and predictive scheduling of irrigation.

### C++ Embedded System
- The core system logic is implemented in C++ on an Arduino microcontroller.
- The C++ code collects real-time data from sensors, processes it, and sends it to the cloud.
- Actuators, such as water valves, are controlled based on real-time conditions and user inputs.

### IoT Sensors and Actuators
- The system uses soil moisture, temperature, and humidity sensors to gather environmental data.
- Water valves are controlled either automatically based on sensor readings or manually via the cloud interface.

## Technologies Used
- **Programming Language:** C++ (for embedded system development)
- **Cloud Platform:** MQTT protocol for real-time communication with cloud storage and dashboard.
- **Hardware:** Arduino microcontroller, soil moisture sensors, temperature and humidity sensors, and water valves.
- **Dashboard:** Cloud-based dashboard for remote monitoring and control.

## Output on Cloud

![Screenshot 2024-09-16 185138](https://github.com/user-attachments/assets/4a36de00-b192-4e72-93fa-326df1bc4390)
![Screenshot 2024-02-21 001011](https://github.com/user-attachments/assets/2d8dc0c0-9f5c-428f-8c67-d34ec591afea)

