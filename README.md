# IoT-Based Water Level Monitoring System

## Overview
This repository contains the code, report, and PowerPoint presentation for an IoT-based water level monitoring system developed by Vishal Singh and led by Vedant Kumar. The system utilizes an ESP32 microcontroller, ultrasonic sensor, and Blynk app to monitor water levels in tanks remotely and provide real-time notifications to users.

## Project Components
- **ESP32 Microcontroller:** Acts as the central hub for collecting data from the ultrasonic sensor and interfacing with the Blynk app.
- **Ultrasonic Sensor:** Measures water levels in tanks by emitting ultrasonic pulses and calculating the distance based on the time taken for the pulses to return.
- **Blynk App:** Provides a user-friendly interface for monitoring water levels remotely and receiving notifications in case of critical levels.
- **OLED Display:** Displays real-time water level data for local monitoring.
- **LEDs and Buzzer:** Provide visual and audible alerts in case of critical water levels.

## Project Files
- **[Code](resources/code/esp32_working.c):** The C code for the ESP32 microcontroller.
- **[Report](resources/report/report.pdf):** The project report detailing the implementation and findings.
- **[Presentation]([link_to_presentation](https://tome.app/abracadubra-a7c/iot-based-water-level-monitoring-system-clugrlts24zvnpr673s615j6v)):** The PowerPoint presentation for the project.

## Project Implementation
The project was implemented using the Arduino IDE and various libraries, including Blynk and Adafruit SSD1306. The ESP32 microcontroller was programmed to collect data from the ultrasonic sensor, display it on the OLED display, and send it to the Blynk app for remote monitoring. Notifications are sent to users via the Blynk app in case of critical water levels.


## Usage
To use the water level monitoring system, follow these steps:
1. Set up the ESP32 microcontroller with the provided code.
2. Connect the ultrasonic sensor and other hardware components as per the [wiring instructions](https://youtu.be/9geREeE13jc?t=122).
3. Install the Blynk app on your smartphone and create a new project.
4. Configure the Blynk app with the provided authentication token and virtual pins.
5. Upload the code to the ESP32 microcontroller and power on the system.
6. Open the Blynk app to monitor water levels remotely and receive notifications.

## Future Enhancements
- Integration with additional sensors for monitoring water quality and temperature.
- Implementation of predictive maintenance based on data analytics.
- Enhancement of user interface and user experience in the Blynk app.


## Contributors
- **[Vedant Kumar](https://www.linkedin.com/in/vedant-kumar-2249b0254/) (Team Lead):** - Led the project development, implemented code, and ensured project milestones were met.
- **[Vishal Singh](https://www.linkedin.com/in/vishal-singh-326b97227/) (Team Member):** -  Contributed to the development of the project, coordinated tasks, and assisted with testing and documentation.

## License
This project is licensed under the [MIT License](LICENSE).

## Wiring Instructions
Please refer to the [circuit diagram](resources/circuit/circuit_diagram.jpg) for wiring instructions.
