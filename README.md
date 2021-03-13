# Robo-soccer

# Bot Setup
Circuit Diagram:
![alt text](https://www.electronicshub.org/wp-content/uploads/2018/08/Bluetooth-Controlled-Robot-using-Arduino-Circuit-Diagram.jpg)
First is the HC-05 Bluetooth Module. The +5V and GND pins of the Bluetooth Module are connected to +5V and GND of Arduino.
Now, the L298N Motor Driver Module. Digital I/O Pins 9 through 12 of Arduino are configured as Input pins of the Motor Driver and are connected to IN1 through IN4 of the L298N Motor Driver Module. Both the Enable Pins are connected to 5V through provided jumper.

The robot chassis which I am using in this Bluetooth Controlled Robot Car project is supplied with 4 geared motors. Since L298N has slots for only two motors, I have joined the left side motors as one set and the right side motors as other set and connected both these sets to the output of L298N Module.


NOTE: I have used L298N Motor Driver Module to drive the motors of the robot. You can use either this one or L293D Motor Driver Module. If you are using L293D, then check out for the connections.



<img src="https://raw.githubusercontent.com/rahulbiswas12/Robo-soccer/master/9ec1ce5e-913a-4742-8f09-77370eb90332.jpg" width="800px">
