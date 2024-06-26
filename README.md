# Security-System-Using-Camera
About Our security system program is exclusively constructed with Python, boasting a facial recognition system meticulously trained to identify specific human faces. The intelligently designed system promptly alerts administrators when an unfamiliar face is detected, effectively addressing potential security concerns.
Description This project implements a security system that utilizes a camera to monitor and record activity in a specific area. The system can detect motion, capture images or record videos, and raise alerts in case of suspicious events. It aims to provide an affordable and accessible solution for home or small business security.

Table of Contents

Features

Installation

Usage

Configuration 5.Contributing

Features Motion detection: The system can detect motion in the camera's field of view. Image capture: When motion is detected, images are captured and stored for further analysis. Video recording: Optionally, the system can record short videos when significant motion is detected. Alerts: Alerts are sent to a specified email or phone number when suspicious events occur. Web interface: A user-friendly web interface allows users to monitor the camera feed and access recorded media.

Installation To set up the Security System, follow these steps:

Clone the repository:

 Navigate to the project directory:

bash Copy code cd Security-Sytstem-Using-Camera- Install the required dependencies:

Copy code pip install -r requirements.txt

Usage Configure the system settings (see Configuration).
Run the main application:

Configuration Before running the system, configure the following settings in config.py:
4.1. Camera settings: Set the camera source (e.g., webcam, IP camera) and resolution. 4.2. Motion sensitivity: Adjust the motion detection sensitivity level. 4.3. Alert settings: Enter the email or phone number to receive alerts. 4.5. Storage: Specify the directory for storing images and videos. Example configuration:

python Copy code
