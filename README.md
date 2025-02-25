Home Safety Monitoring System

Description

The Home Safety Monitoring System is an IoT-based safety solution that detects gas leaks, smoke, and excessive carbon monoxide (CO) levels in a home or workplace. The system uses an ESP8266 Wi-Fi module to communicate with the Blynk app, allowing users to monitor real-time sensor data and receive instant alerts if dangerous levels are detected. Additionally, it triggers an automated safety response such as activating a buzzer, turning on a fan, and operating a servo motor to take preventive actions.

Components Used

ESP8266 Wi-Fi Module - Provides wireless connectivity.

MQ2 Gas Sensor - Detects gas leaks and smoke.

Flame/Smoke Sensor - Monitors smoke concentration in the air.

CO Sensor - Detects dangerous carbon monoxide levels.

Servo Motor - Activates emergency mechanisms in case of danger.

Buzzer - Sounds an alert in case of hazardous conditions.

LED Indicators (Green/Red) - Shows safe (green) and danger (red) states.

Fan - Turns on to disperse gas and improve air quality.

Blynk App - Displays real-time sensor data and sends alerts.

Features

✅ Real-time Monitoring - Continuously tracks air quality and detects gas leaks.

✅ Blynk App Notifications - Sends alerts for gas leaks, smoke, and CO levels.

✅ Automated Safety Measures - Turns on the fan and buzzer in case of danger.

✅ Wireless Control - Users can monitor and manage the system remotely.

✅ Emergency Servo Activation - Operates a servo motor to initiate emergency actions.

Use Cases

Home Safety - Prevents fire accidents and gas leaks in households.

Industrial Monitoring - Ensures workplace safety by monitoring hazardous gas levels.

Smart IoT Integration - Can be a part of a smart home or industrial safety system.

How It Works

The sensors continuously measure gas, smoke, and CO levels.

If any value exceeds the safety threshold, an alert is sent via the Blynk app.

The buzzer and red LED turn on, indicating danger.

The fan is activated to help disperse the hazardous gas.

A servo motor is triggered for emergency measures.

The user can also manually control the system through the Blynk app.

Installation & Setup

Hardware Setup:

Connect the sensors to the ESP8266 module.

Attach the servo motor, fan, and buzzer.

Software Configuration:

Install the Blynk app and create a project.

Use the provided Auth Token for connectivity.

Upload the Arduino code to the ESP8266 using the Arduino IDE.

Run the System:

Power on the system and start monitoring via Blynk.

Future Improvements

Integration with additional safety devices like fire alarms.

AI-based predictive analysis for hazardous conditions.

Mobile app enhancements for better user control.

Contributors

Project Developed By: [Your Name]

Technologies Used: IoT, Blynk, C++, Arduino IDE, ESP8266

This system provides an efficient and real-time safety solution to prevent hazardous situations in homes and workplaces.

