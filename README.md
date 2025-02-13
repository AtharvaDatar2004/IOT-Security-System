# IOT-Security-System

*Company* : CODTECH IT SOLUTIONS

*NAME* : ATHARVA ABHAYKUMAR DATAR

*INTERN ID* :CT08MBP

*DOMAIN* : INTERNET OF THINGS

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

# DESCRIPTION OF THE TASK

Objective:
The IoT Security System is designed to enhance home or office security by detecting motion, capturing images or video, and sending real-time alerts to a mobile app or web dashboard. It will use sensors, cameras, and an IoT platform to provide remote monitoring and instant notifications in case of unauthorized access.

Key Features:
1.Motion Detection: Uses PIR sensors or camera-based motion tracking to detect intrusions.
2.Real-Time Alerts: Sends instant notifications via Blynk, Firebase, or MQTT when motion is detected.
3.Live Camera Feed (Optional): Streams real-time video from an ESP32-CAM or IP camera to a smartphone or web interface.
4.Image Capture & Storage: Captures images of intruders and stores them in cloud storage or local memory.
5.Buzzer or Alarm: Triggers an alarm to deter intruders.
6.Access Control (Optional): Integration with RFID, fingerprint scanner, or keypad for secure entry.
7.Mobile & Web Control: Users can arm/disarm the system remotely using a smartphone app or web dashboard.
8.Power Backup (Optional): Battery-powered operation for security during power failures.

Components Required:
Microcontroller: ESP32, ESP8266, or Raspberry Pi
PIR Motion Sensor: Detects movement
Camera Module (Optional): ESP32-CAM or IP camera for image/video capture
Buzzer/Alarm: Triggers sound alerts
Relay Module: Controls external alarms or lights
IoT Platform: Blynk, Firebase, MQTT, or ThingsBoard for remote monitoring
Cloud Storage (Optional): Google Firebase or SD card for storing captured images
Power Supply: 5V USB adapter or battery backup

Working Principle:
1.The motion sensor detects any movement in the secured area.
2.If movement is detected, the camera (if used) captures an image or video.
3.The system sends an alert (via push notification, SMS, or email) to the user.
4.The user can view live video or review stored images on the mobile app or web dashboard.
5.If an intruder is detected, the alarm sounds, and the system can trigger additional security actions.
