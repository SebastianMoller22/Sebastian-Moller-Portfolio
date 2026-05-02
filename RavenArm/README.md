## Portable Raven arm Driver

<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/IMG20251031160033.jpg" height="400" alt="compeletbuild">

During the months after my graduation, *...* contacted me to help with developing a mechanical driver for the Raven 2 surgical robot adaptor. The goal of this project was as follows:
- Drive all actuator components similarly to that of the main raven body
- Make it small and portable
- Allow serial communication to control it
- have an attachment point so it can be used on different robotic arms
- Calibrate the encoders
- run all code from an Arduino Nano
- document setup and assembly
- connect the arm to an OMEGA 7 controller

This adaptor involved making a box that would house the actuators that would drive the Raven tool. This required me to use the CAD models to accurately make replica riving tools to attach to the raven tool. The housing is required to be durable and secure so that it can be used for demonstration and constant use. This housing took several small iterations to complete so that it would fit securely, and the actuator will accurately work the raven tool.

After which, I had to code several scripts to perform the required action. First, I had to calibrate the actuators to the extremes of the Raven tool. This was due to the raven tool being able to attach in multiple orientations, and the encoder would only remember the previous positions.

To complete this, I ran a small sequence script that would move each actuator slowly, moving the tool. Once it reached the end of its capabilities, it would spike the current, and I would reverse the direction for the other extreme. This was performed for all the actuators, except for a small addition was made for the last 2, requiring them to fully open the grippers before calibrating. 

Once fully calibrated, it would send data for each of the actuators' position, goal position and current velocity serially so it can be used by other programs to determine what actions to do. 

<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/omega6v.jpg" height="400" alt="OMEGA7">

One of the main components that would be used in the serial communication was the OMAGA 7 controller. By utilising 4 of its sensors, I was able to control it manually and was able to ‘feel’ when it had grabbed something. This was done by using the output current and a ratio to control the amount of torque and force the OMEGA 7 output put through the controller. 

This project was found to be successful and is in use to this day. 

<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/IMG20251031160042.jpg" height="400" alt="Complete Build">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/IMG20251031160047.jpg" height="400" alt="Complete Build">