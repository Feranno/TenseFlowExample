### About the _FIRST_ Tech Challenge
The _FIRST_ Tech Challenge seeks to inspire youth to become the next generation of STEM leaders and innovators through participation in mentor-guided robotics competition.  Teams who participate in the _FIRST_ Tech Challenge must build a robot that performs a variety of tasks.  The tasks vary from season to season, and are based on a set of game rules that are published at the start of each season. The more tasks that a robot can complete, the more points a team will earn.

<p align="center"><img src="https://github.com/FIRST-Tech-Challenge/WikiSupport/blob/master/ftc_app/images/HoustonMatchPlay.jpg" width="500"><br/>(Photo courtesy of Dan Donovan, ©2017 Dan Donovan / www.dandonovan.com)<p>


### Autonomous vs. Driver-Controlled
A _FIRST_ Tech Challenge match has an _autonomous_ phase and a _driver-controlled_ or _"tele-operated"_ phase.  In the autonomous phase of a match the robot operates without any human input or control.  In the driver-controlled phase, the robot can receive input from up to two human drivers.

### Point-to-Point Control System
The _FIRST_ Tech Challenge uses Android phones to control its robots.  During a competition, each team has two Android phones.  

<p align="center"><img src="https://github.com/FIRST-Tech-Challenge/WikiSupport/blob/master/ftc_app/images/PointToPointControl.jpg" width="500"><p>

One phone is mounted onto the robot and is called the _Robot Controller_.  The Robot Controller acts as the “brains” of the robot.  It does all of the thinking for the robot and tells the robot what to do. It consists of an Android device running an FTC Robot Controller app.

A second phone sits with the team drivers and has one or two gamepads connected.  This second phone is known as the _Driver Station_.  The Driver Station is sort of like a remote control that you might use to control your television.  The Driver Station allows a team to communicate remotely (using a secure, wireless connection) to the Robot Controller and to issue commands to the Robot Controller.  The Driver Station  consists of an Android device running an FTC Driver Station app.

### REV Robotics Expansion Hub
The REV Robotics Expansion Hub is the electronic input/output (or “I/O”) module that lets the Robot Controller talk to the robot’s motors, servos, and sensors.  The Robot Controller communicates with the Expansion Hub through a USB connection.  The Expansion Hub is connected to a 12V battery which is used to power the Expansion Hub, the motors, the servos and sensors.  The Robot Controller typically has its own internal battery, which can also be charged through the USB cable connected to the Expansion Hub.

<p align="center"><img src="https://github.com/FIRST-Tech-Challenge/WikiSupport/blob/master/ftc_app/images/REVExpansionHubLayout.jpg" width="600"><p>

### What's an Op Mode?

During a typical FIRST Tech Challenge match, a team’s robot has to perform a variety of tasks in an effort to score points.  For example, a team might want their robot to follow a white line on the competition floor and then score a game element (such as a ball) into a goal autonomously during a match. Teams write “op modes” (which stand for “operational modes”) to specify the behavior for their robot.

_Op modes_ are computer programs that are used to customize the behavior of a competition robot.  The Robot Controller can _execute_ a selected op mode to perform certain tasks during a match.

Teams who are participating in the _FIRST_ Tech Challenge have a variety of programming tools that they can use to create their own op modes.  Teams can use a visual ("drag and drop") programming tool called the _FTC Blocks Programming Tool_ to create their op modes.  Teams can also use a text-based Java tool known as the _FTC OnBot Java Programming Tool_ or Google's _Android Studio_ integrated development environment (also known as an "IDE") to create their op modes. 