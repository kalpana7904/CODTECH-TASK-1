# CODTECH-TASK-1
## Name:P.kalpana
## Company:CODETECH IT SOLUTIONS
## ID:CT06DF1896
## Domain:Embedded Systems
## Duration:May to july
## Mentor:Neela Santhosh kumar
## OVERVIEW of the project
## Project:Temperature Monitoring System - Project Overview
## CIRCUIT DIAGRAM: ![Uploading WhatsApp Image 2025-06-17 at 17.09.59_82dc4072.jpg…]()
## Project Purpose
This project creates a real-time temperature monitoring system that measures ambient temperature and displays the readings through both a physical LCD screen and a computer's serial monitor.

## Key Components

### Hardware
- Microcontroller: Arduino Uno (the brain of the system)
- Sensor: LM35 precision temperature sensor (converts temperature to electrical signals)
- Display: 16×2 LCD with I2C interface (for visual output)
- Interface: I2C module (simplifies LCD connections)
- Supporting Components: Breadboard and jumper wires

### Software
- Arduino IDE programming environment
- Custom code handling temperature reading and display functions
- Libraries for LCD communication (Wire.h and LiquidCrystal_I2C.h)

## How It Works

1. Temperature Sensing:
   - The LM35 sensor generates an analog voltage proportional to temperature (10mV per °C)
   - Arduino reads this voltage through its analog-to-digital converter (ADC)

2. Data Processing:
   - The raw ADC value is converted to voltage
   - Voltage is then converted to temperature in Celsius
   - Calculations account for the sensor's 10mV/°C characteristic

3. Output Display:
   - LCD Screen: Shows current temperature with "°C" units
   - Serial Monitor: Provides detailed temperature logs for debugging

## Technical Features

- Dual Output: Simultaneous display on LCD and serial monitor
- Precision: LM35 provides ±0.5°C accuracy at room temperature
- Refresh Rate: Updates every second for real-time monitoring
- Simple Calibration: No need for complex calibration due to LM35's linear output

## Applications

This system can be adapted for:
- Home temperature monitoring
- Laboratory equipment
- Industrial process monitoring
- Educational demonstrations of sensor systems
- Data logging applications (with additional code)

## Expansion Possibilities

The basic design can be enhanced with:
- Additional sensors (humidity, pressure)
- Data logging to SD card
- Wireless transmission capabilities
- Temperature alerts and thresholds
- Web-based monitoring interface
- ## Output demonstration: ![WhatsApp Image 2025-06-17 at 17 10 55_43411286](https://github.com/user-attachments/assets/29467e53-24f9-4d53-8e27-37cb0f42f259)

- 
- 
