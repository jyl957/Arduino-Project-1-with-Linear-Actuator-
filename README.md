# Arduino-Project-1-with-Linear-Actuator-
Project Description： The linear actuator will push valve to a new position when the distance between the hand and sensor is larger than 2cm and less than 9cm. The linear actuator will push valve back to the original position when the distance is larger than 9cm and less than 16cm. This system can be used to control faucet or valve. Compared with traditional control system by using infrared sensor. This system can keep valve open without holding the hand in front of the sensor. 

Project Responsibility：The distance was determined by using ultrasonic senor. The different pulse width modulation signals generated from Arduino were sent to a SR-Latch to hold or reset the current state of valve. The output pin of SR-Latch was connected to A0 pin. The movement of linear actuator is determined by processing the output of SR-Latch.



![image](https://github.com/jyl957/Arduino-Project-1-with-Linear-Actuator-/blob/main/circuit_diagram.png)
