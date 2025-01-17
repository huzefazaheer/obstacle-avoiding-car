# Obstacle Avoiding Car
A esp-32 based car that uses a HC-SR04 ultrasonic distance sensor to detect objects, then following an algorithm to make its away out of tricky situations.

## Hardware:
1. Esp32
2. HC-SR04
3. L298N Motor Driver
4. 4x Brushless DC Motors

There are four motors, two of which in either side are connected in parallel. They both feed into the motor driver which takes in signal from the esp-32 to determine what direction and speed to spin the motors in. The direction and speed is determined by the arduino based on data fed by the ultrasonic sensor.

Further improvements can be made to this design by incorperating more sensors to allow for more autonomous features. An alternative approach could be to train a Machine Learning model to navigate the terrain
