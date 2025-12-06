# Robot Code
Line following robot with IR Sensors and Ultrasonic Sensor

The code for the line-following apparatus using the infrared sensors and motors is partially sourced from instructables.com and Microsoft’s Copilot Ai. The code has multiple parts: multiple segments for the line following mechanism, including stopping and turning the wheels, and the obstacle avoidance system. For each group of code, the name of the function is above it.

Define and int statements are used for cleaness.

Multiple void statements are used so that functions can be inputted into later functions, simplifies code.

The Ultrasonic Sensor obstacle detection code is placed before the movement in the "void loop ()" so it will override the movement code (because it runs first).