# Bluetooth-Controlled-Home-Automation-System
A home automation system that allows users to control home appliances  (like lights, fans, etc.) remotely using a smartphone via Bluetooth. This system will  include status display, and manual override options.

## Core Features:

### 1. Appliance Control via Bluetooth:
Hardware: Bluetooth module (HC-05), DC motor, Servo motor, Stepper motor, LEDs, DIP switches.

Control appliances like lights (simulated by LEDs), fan (using a DC motor), door (using a Servo motor), and blinds (using a Stepper motor) through Bluetooth commands from a smartphone app.


### 2. Manual Override:
Hardware: push buttons. Allow the user to manually control appliances in case of Bluetooth failure or preference for physical control.


### 3. Status Display:
Hardware: Character LCD. Show the current status of appliances (on/off, speed, etc.) on the LCD.


### 4. Data Logging & System Monitoring:
Hardware: External EEPROM. Log data related to system usage (devices states) and store them in the EEPROM for future analysis.


### 5. Feedback System for User:
Hardware: Buzzer (for sound feedback). Notify the user when an action is taken via sound, providing auditory 
confirmation for successful commands.

