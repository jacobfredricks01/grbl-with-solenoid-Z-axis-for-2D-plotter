# grbl-with-solenoid-Z-axis-for-2D-plotter
GRBL version 1.1 but with a binary Z-axis that uses PWM from digital pin 11 on an Arduino UNO to actuate a solenoid to move a writing utensil up and down

Copied from https://github.com/bdring/Grbl_Pen_Servo with slight modifications.  

In the spindle.c file there are 2 definitions, "pen_servo_up" and "pen_servo_down" these values are directly related to the PWM output of digital pin 11 on an Arduino UNO.  
