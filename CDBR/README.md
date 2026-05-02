## Thesis Projcet: Cable-Drive Bimanual Robot Manipulation for Collaborative Workspaces

<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/IMG20250521120141.jpg" height="400" alt="">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/IMG20250521120115.jpg" height="400" alt="">

This project is my thesis project that completed my mechatronics degree. This project was made up of 2 supervisors, **Will Browne** and **Krishna Manaswi Digumarti** and 2 undergraduate students, **Josh Roe** and **me**. The project involved designing and developing a Bimanual Cable drive robot that could travel around the office level while performing manual tasks like brewing and delivering coffee. This would require it to navigate around the office space while transitioning from hard, smooth surfaces to carpet. As well as being able to open and close a room door and perform dexterous actions while holding objects.\
\
Due to the project's size, it was determined that this project would be broken down and given as individual projects to multiple students. As a result, I was given the goal of designing all the hardware components and electrical integration of the bimanual arms.\
\
This required me to perform multiple tests to determine the required force each arm would be required to withstand, as well as the minimum number of degrees of freedom to perform the required goals.\
\
This project required me to use my skills in:
- Testing
- Recording data
- Analysing Data
- Constructive Debating and Discussion
- Applying Engineering Principles (In relation to safety)
- CAD Design
- Simulation
- RPD (Rapid Prototype Development)
- PCB Design
- ROS2 coding
- Serial communication between multiple coding languages and devices
- Report Writing

At the end of the project, it was agreed upon that I had completed my goals for my thesis, the project was found to be prepared for other students to complete more part of the project after **Josh** and **I** had departed. And I ended this unit with a high distinction due to my outstanding project development and final report showing all iterations and engineering design choices.\
\
Below are the key components of my contribution to the project\

### Data Collection and Analysis
I had to find the required length to light various objects to determine the required strength of each arm. The key lighting requirements were as follows:
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Force_tests.png" height="600" alt="Test image">

- lifting a full kettle (2)
- moving a door handle (3)
- overcoming the initial friction force of a door (4)
- moving the door completely open (4)

I made a small measuring device (1) to determine the forces required to complete these tasks. From the test, each required less than 2.5kg of Equivalent Lifting Force, and as a result, the factor of safety was set at 3kg ELF at 600mm.

### Arm Griper
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Gripper%201.png" height="900" alt="Gripper 1">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/gripper%202.png" height="400" alt="Gripper 2">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Gripper%203.png" height="400" alt="Gripper 3">

The gripper was designed to be able to securely grab a standing mug. It went through 3 iterations. The fixed and linear mobile gripper, this was found to complect and big. The second used a gear design to move 2 flexible grippers to grasp the mug; it was found that the flexible grippers weren't sturdy enough to hold a mug. The last design used the same gears but replaced the flexible grippers with a bone design, allowing it to hold a mug without flexing too much

## Gripper Rotation
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Wrist%20com.png" height="400" alt="Test image">

A wrist-like attachment was designed for the gripper; however, due to hardware restrictions, this couldn't be implemented (limited number of actuators)

## Arm Joints
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%201.png" height="400" alt="Joint 1">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%202.png" height="400" alt="Joint 2">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%203.png" height="400" alt="Joint 3">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%204.png" height="400" alt="Joint 4">

These were the main components of the Bimanual arms. The first concept was a rough idea and didn't make it out of the conception. The second was based on a design called the "Design of Low Inertia Manipulator". This was found to be a lot of promise and was the basis of the concepts going forward. The third design iterated on the second but had geared teeth and adjustable connector rods. This, however, was found to be too weak for the required 3kg of ELF for the project. The fourth and last gearing increase the strength of the design by using stronger 3d printing today, which resulted in it being able to have a 13.5kg ELF at 600mm.

## Arm Lift
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20lift%201.png" height="400" alt="Lift 1">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20lift%202.png" height="400" alt="Lift 2">

The lifting component's first concept was designed during the early stages of the project and was found to be insufficient for the project. As a result, this component was put on hold until the later stages of the project. The second section had 2 sections to sandwich the joints together, while having space for hardware components. 

