MIA Robotics - Electrical Team Training 26/27 - Task 10

Pit crew robot electrical boards, designed in Altium Designer.

Boards

This repo contains three boards, each in its own folder:

1. Actuators Base Board

Controls solenoid valves and servo motors.

STM32F411 BlackPill
Solenoid valve control (ULN2xxx driver)
Servo motor connectors with overcurrent protection
2. Sensors Base Board

Handles motion, orientation, and distance sensing.

STM32F411 BlackPill
MPU6050 (6-axis IMU)
BNO055 (9-axis orientation)
Ultrasonic distance sensor
Limit switch with debounce circuit
I2C ESD protection
3. Power Distribution Base Board

Supplies and protects power for the whole system.

Buck converter (12V to 5V)
Overvoltage, overcurrent, and reverse voltage protection
12V and 5V circuit breaking option (MCU controlled)
Folder Structure

Each board folder contains:

Schematic files
PCB layout files
Libraries used (schematic + PCB)
Bill of Materials (BOM)
