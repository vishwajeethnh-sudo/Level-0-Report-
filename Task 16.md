# Task 16: Report on L293D MOTOR DRIVER.

## INTRODUCTION: 
L293D is a Dual H-bridge motor driver Integrated Circuit used to control the direction and speed of two DC motors. Microcontrollers use low current but motors and actuators use fairly higher current. Now, since microcontrollers cannot directly operate on actuators, L293D Motor Driver is used here as an interface between both of these components.

## WORKING PRINCIPLE: 
L293D Motor Driver works on the principle of H-Bridge configuration, which moves the motors based on the direction of current flow. We can control the direction of current through motors, which changes the direction of motor rotation, through controlling the core logic at input pins. 
The motor uses 2 input pins, namely IN1 and IN2 to control each motor. When enabled, the outputs follow the logic applied at the input pins.

- When IN1 = HIGH and IN2 = LOW, current flows in one direction through the motor, causing it to rotate clockwise.

- When IN1 = LOW and IN2 = HIGH, the current flows in the opposite direction, causing the motor to rotate counterclockwise.

- When both inputs are LOW or both are HIGH, the motor stops because there is no effective potential difference across it.

The outputs of the L293D provide the required current and voltage to the motor, while the microcontroller only supplies the control signals. This allows safe and efficient motor control without damaging the microcontroller.

## COMMON APPLICATIONS:
- Robotics
- Automated vehicles
- Conveyer belt systems
- Home automation system
- Toy motors
- Educational and laboratory purposes

## CONCLUSION:
The L293D is a Motor Driver IC used for controlling actuators. It is used as an interface between microcontrollers and motors to safely operate them. It protects the control circuit from high current and voltage spikes. systems. It can control the rotation of DC motors in both forward and reverse directions (also used in control the speed of DC motors).
