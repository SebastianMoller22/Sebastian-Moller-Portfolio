## Thesis Projcet: Cable-Drive Bimanual Robot Manipulation for Collaborative Workspaces
This projcet is my thesis project that completed my mecahtronics degree. This project was made up of 2 supervisors, **Will Browne** and **Krishna Manaswi Digumarti** and 2 undergraduated **Josh Roe** and **me**. The project invoved desing and developing a Bimanual Cbale drive robot that coudl travel around the office level while perfroming medial task like brewinga nd deliveruing a coffee. This would require it to navicage areoun the office space while transitioning from hard smooth surfaces and carptit. Aswell as being able to open and close a room door and perform dextras action with held objects.\
\
Due to the projcets size it was determened that this project would be brokecn down and given as individual rpoject to mutiple theis students. As a result I was given the goal of desiging all the hardware complonents and electrical integration of the bimanual arms.\
\
This required me to perform mutiple tests to detemrin the required force each arm would be required to withstand as well as the minium number of degree of freedmosm to perform the required goals.\
\
This poject required me use my skills in:
- Testing
- Recording data
- Analysing Data
- Constructive Debasting and Disscustion
- Applying Engineering Principles (In relation to saftey)
- CAD Design
- Simulation
- RPD (Rapid Prototype Development)
- PCB Design
- ROS2 coding
- Serial comunication between mutiple coding languages and devices
- Report Writing

At the end of the project it was agreed apon that i have compledt my goals for my theis, the project was found to be prepared of other student to complte more part of the project after **Josh** and **I** had departed. And I ended this unit with a high desinction due to me outstandiong project development and final reprot showing all itteration and engrineering ding design choses.\
\
Below are the kwy componets of my contrubution to the project\

### Data Collection and Analysis
I hade to fidn the requied for to light various object to determin the required stingth oif each arm. the key ligting requirment were as follows:
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Force_tests.png" height="400" alt="Test image">

- lifting a full kettle (2)
- mobing a door handle (3)
- overcomming the inital frication force of a door (4)
- moving the a door completly open (4)


I made a small mesuing device (1) to deteioming the forces required to comple these taskas. From the test each required less then 2.5kg of Equivelant Lifting Force and as a result, the factor of saftey was set a 3kg ELF at 600mm.

### Arm Griper
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Gripper%201.png" height="400" alt="Test image">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/gripper%202.png" height="400" alt="Test image">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Gripper%203.png" height="400" alt="Test image">

The gripper was deisng to being able to secyorly grab a stand mug. it went though 3 itteration. The fixed and linear mobimg gripper, this was found to complect and big. The secon used a gear desing to move 2 fexable grippers to grasp the mug, it was fing thatthe fexable grippers weren't sturdy enough to hold a mug. The las desing used that same gears but replaced thet flexabel grippers with a bone design alowed it to hold a mug witout flexing too much

## Gripper Rotaion
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/Wrist%20com.png" height="400" alt="Test image">

A wrist like attacment was desing for the gripper howver due to hardware restricteion this couldn't be implamented (limited number of actuators)

## Arm Joints
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%201.png" height="400" alt="Test image">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%202.png" height="400" alt="Test image">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%203.png" height="400" alt="Test image">
<img src="https://github.com/SebastianMoller22/Sebastian-Moller-Portfolio/blob/main/Images/arm%20joint%204.png" height="400" alt="Test image">

These were the main componet of the Bimanul arms. The first concept was was a roughj idea and didn't make it to the out of the conception. The second was based on a desing called the "Design of Low Inertia Manipulator". This was found to bahe alot of promis and was the basis of the concets going forward. The thrid desing itterted on the secon bu haveing geared teeth and agustable connector rodes. this hwover was found to be too weak for the required 3kg of ELF for the projcet. The fourth and last geaing increase the strength of the deisng by using stronger 3d printing tecnighs wich resulted in it being able to have a 13.5kg ELF at 600mm.

## Arm Lift





