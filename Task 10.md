# Task 10: Speed Control of DC motor
## Objective
Understand basic techniques for controlling DC motors. Learn how an L298N motor driver works. Control the speed and direction of a 5V BO motor using an Arduino UNO and L298N motor driver. Simulate the circuit in Tinkercad. Implement the same setup on real hardware. 
## Procedure 
The speed of a DC motor is controlled using PWM (Pulse Width Modulation). The arduino UNO provides PWM signals. Speed control of DC motor can be understood by "Higher duty cycle means Higher average voltage which gives Higher speed and Lower duty cycle means Lower speed".

The L298N motor driver uses an H-Bridge configuration to Control motor direction,Provide sufficient current to drive the motor, Protect the Arduino from high current draw. Direction is controlled using two input pins: IN1 HIGH, IN2 LOW implies Clockwise direcation and. IN1 LOW, IN2 HIGH give Anticlockwise.

All of these are connected in tinkercad to run the simulation an =d check for results. If correct then the connections are made in real hardware and output is taken down.

## Learning
Through this task, the following concepts were understood Working principle of DC motors, PWM-based speed control, L298N motor driver operation, Interfacing motors with microcontrollers, Importance of external power supply, Simulation before hardware implementation.
