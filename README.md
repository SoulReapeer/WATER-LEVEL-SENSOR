**Water Level Indicator using Arduino Uno**

This project is a simple Water Level Indicator built with an Arduino Uno. It uses a water level sensor to monitor tank levels and displays real-time readings on an LCD (16x2) with an I2C module. The project can be extended with buzzers or pumps for automation.


**Features**

- Measures water level using an analog sensor

- Displays water level value and status (Empty, Low, Medium, High) on LCD

- Sends real-time sensor values to the Serial Monitor

- Compact design using an I2C module for LCD


**Components Used**

- Arduino Uno board × 1

- Water Level Sensor × 1

- LCD Display (16x2) × 1

- I2C Module × 1

- Jumper wires


**Circuit Connections**

------------------------------------
| Component          | Arduino Pin |
|--------------------|-------------|
| Water Level Sensor | A0          |
|--------------------|-------------|
| LCD (via I2C)      | SDA → A4    |
|                    | SCL → A5    |
|--------------------|-------------|
| Power (VCC, GND)   | 5V, GND     |
------------------------------------
