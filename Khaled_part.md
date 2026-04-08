Actuator Selection and Performance Analysis

Motors are one of the most important parts of a robotic system because they convert electrical energy into mechanical motion. In our project, the motor choice was based on torque, speed, power consumption, and how easily it can be controlled with the rest of the system. For the robot platform, we selected a DC geared motor with an encoder because it gives smooth motion, stable performance, and accurate feedback for control.

The figure below shows the motor calculations used to justify this selection. The motor speed was analyzed at 166 RPM, which gives a linear speed of about 0.565 m/s, and the power check showed 2.7 W per motor and 5.4 W for two motors. These results support the use of a low-RPM motor because it provides smoother movement and makes the platform easier to control.

Torque Calculation and Actuator Requirement

Torque is a key factor in robotic arm design because each joint must carry the weight of the arm and the object being handled. To make the arm strong enough, we calculated the required torque using the arm dimensions and an assumed load. The maximum torque of the selected motor is 30 kg·cm, which is equal to about 2.94 N·m, and this was used as the starting point for the design.

The torque calculations in the figure show that the payload torque, arm weight torque, and safety factor were all included. The total required torque for the main joint was found to be about 1.85 N·m, while the shoulder joint required about 4.34 N·m. Because this joint needs more force, two actuators were used together to increase torque and ensure safe operation.[Electrical Architecture]()

