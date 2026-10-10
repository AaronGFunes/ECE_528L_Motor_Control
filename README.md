# ECE 528/L - Robotics and Embedded Systems with Lab
**CSU Northridge**

**Department of Electrical and Computer Engineering**

## Motor Control Lab
The Motor Control lab interfaces with the following:

* User LEDs of the TI MSP432 LaunchPad
* Pololu Gearmotor with Encoder - [Product Link](https://www.pololu.com/product/3675)
* Left Bumper Switches for TI-RSLK MAX - [Product Link](https://www.pololu.com/product/3673)
* Right Bumper Switches for TI-RSLK MAX - [Product Link](https://www.pololu.com/product/3674)
* HS-485HB Servo-Stock Rotation - [Product Link](https://www.servocity.com/hs-485hb-servo/)


## Overview
Build C project and develop functions for PWM design and DC motor control. An introduction to interrupts in relation to the bumper switches is also introduced with a function to move in a predefined drive pattern. 

## Components Used
    - MSP432 LaunchPad
    - USB-A to Micro-USB Cable
    - TI-RSLK MAX Chassis
    - Bumper Switches
    - HS-485HB Servo
    - Oscilloscope
    - Oscilloscope Probes


## Analysis and Results
Servo 0 degrees Pulse Width
![Servo 0 degrees Pulse Width](/screenshots/ece528L_lab1_servo_0_degrees_pulse_width.png)

Servo 180 degrees Group
![Servo 180 degrees Group](/screenshots/ece528L_lab1_servo_180_degrees_group.png)

Servo 180 degrees Pulse Width
![Servo 180 degrees Pulse Width](/screenshots/ece528L_lab1_servo_180_degrees_pulse_width.png)

Bumper Terminal Output
![Bumper Terminal Output](/screenshots/ece528L_lab1_bumper_terminal_output.png)

Bumper Scope Shot
![Bumper Scope Shot](/screenshots/ece528L_lab1_bumper_scope_shot.png)


## Known Issues or Limitations

Current issues ran in to PWM pulse width timing. Timing period were off based on oscilloscope values. Issues were also found with Drive_Pattern_1(), Motor did not seem to run after building and programming board.


## References

