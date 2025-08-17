Automated Pet Feeder System
Overview
The Automated Pet Feeder is a smart system designed to schedule and dispense pet food at predefined times and portions. It ensures your pet is fed on time, monitors food dispensing, and alerts you in case of issues like an empty food bin or uneaten food.

Features
Scheduled Feeding: Set multiple feeding times and portion sizes via keypad.
Real-Time Clock (RTC): Accurate timekeeping for feeding schedules.
Food Dispensing Verification: Uses weight sensors to confirm food delivery.
Consumption Monitoring: Detects if the pet eats within a set time.
Alerts & Notifications: LCD display alerts; optional Wi-Fi/Bluetooth notifications.
Data Logging: Records feeding events with timestamps.
Fail-Safe Mode: Dispenses default portion if sensors fail.
Hardware Components
Microcontroller: Arduino Uno / Mega (or Raspberry Pi for advanced features)
RTC Module: DS3231
Servo Motor: SG90 or MG995
Weight Sensor: HX711 + Load Cell
Display: 16x2 LCD or OLED
Keypad: 4x4 matrix keypad
Optional: ESP8266/ESP32 for IoT connectivity, SD card for logging
How It Works
Power On: Displays current time on LCD.
Set Schedule: Input feeding times and portion sizes via keypad.
Monitor Time: Continuously checks RTC for feeding time.
Dispense Food:
Check food bin level.
Activate servo to dispense portion.
Verify weight increase.
Alert if food not dispensed.
Monitor Consumption:
Start timer (default 10 min).
Detect weight decrease.
Alert if food not eaten.
Log Event: Save feeding details and update LCD.
Future Enhancements
Mobile app integration for remote control.
Camera-based pet monitoring.
Voice alerts and AI-based feeding recommendations.
License
MIT License



