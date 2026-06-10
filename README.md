# Our 2026 HackClub Fallout Project
Presented by Tyler Bergsma and Andy He (With a TON of CAD help from Keegan O'Neil)

## Our Project

We decided to make a Nerf Rival shooting mecanum-drive differential-turret robot that has auto aiming built in. This came from a love of robotics from all of us, and also because we all enjoy Nerf battles and guns.  Here's an example of what we wanted the turret to look initially:


The next most meaningful part of the robot is the drivetrain, which we decided would use mecanum wheels to give our robot incredibly diverse and versatile movement. Paired with the strong 600RPM motors we plan to use, this should give us a very snappy and responsive bot. 
Because our robot will be mostly 3d-printed out of PETG, it should be very durable, and the underlying frame (made of aluminum) brings that up even more.
Our camera system on the robot should also be extremely robust, using 3 cameras in total- 2 for general operator vision and 1 to give an onbaord raspberry pi access to auto-aiming features so that the robot can aim fully autonomously. We plan to send the camera input back to Tyler's Steamdeck OLED for processing and for human controller input. Speaking of sending information back and forth, the robot will use a 2.4Ghz WiFi adapter to connect to a local network and allow it to stream video and control signals back and forth. This gives us extremely low latency and high quality video, as well as the added benefit of being able to possibly be connected to LTE farther down the line and be controlled from anywhere in the world.
To shoot the Rival rounds, we plan to use two flywheels and shoot them around ~110-120fps in total, giving them some kick for a relatively short spin up time and a small amount of downtime per shot.

Here's a picture of our full 3D model (done in onshape), to show what we mean by all that:

<img width="502" height="459" alt="2026-06-09-221540_hyprshot" src="https://github.com/user-attachments/assets/e3d92b47-39da-4822-844e-5778e08bde54" />

<img width="503" height="468" alt="2026-06-09-221526_hyprshot" src="https://github.com/user-attachments/assets/ab93dae1-586f-4a7a-b8dc-3817979870fd" />

<img width="554" height="504" alt="2026-06-09-221514_hyprshot" src="https://github.com/user-attachments/assets/94244615-2d19-4b52-be7b-333327510889" />

<img width="475" height="432" alt="2026-06-09-221500_hyprshot" src="https://github.com/user-attachments/assets/c1007720-a5ed-4f98-b715-6ac5656dedc3" />

<img width="464" height="425" alt="2026-06-09-221433_hyprshot" src="https://github.com/user-attachments/assets/6c8f31fa-4416-4101-ae8a-9937e29af8b8" />

And here's a screenshot of the base chasis that we plan to use:



## Our Process

A full Bill of materials (BOM) can be found at the resources section at the bottom of our README.
To start off, first we figured out the major components we would use in our project and what mechanisms or devices we would use to bring our bot to life. This included creating a list of all of the parts we need with links, so that we'd also hopefully be able to find their dimensions and other specs. This took only around and hour with some very intensive googling and queries to Claude.
The next most important task was to CAD it upp! Our amazing half-team-member Keegan the CAD monster did all of this, creating the whole external structure of the bot including all of the mounts and such in OnShape.
Once our project gains monetary approval, we plan to 3D-print all of the parts we need from various colors of PETG on Tyler's A1-Mini and Ender-3. We also hope to possibly use the P2S in our robotics team lab to hopefully be able to print some of the larger parts quickly.

## US!

There are three of us working on this project. We are Tyler Bergsma, Keegan O'Neil, and Andy He. Unfortunately, Keegan won't be coming with us to Shenzen, but he was an AMAZING help to our lackluster CAD abilities. We're all from Denver, Colorado, U.S.A., and we all attend Chatfield Senior High, where we are a part of the schools local FIRST robotics team, [The Chargers (Team 9068)](https://Chatfieldrobotics.org). All three of us love robotics and mechanical/programming stuff, which is a huge part of why we chose to do what we did with this event. 

## BOM

- Drivetrain
    - JGB37-520 12V 600 RPM Motors
    - BTS7960 43A H-Bridge Motor Driver
    - 60mm Mecanum Wheel Omnidirectional Wheel Smart Robot Car Chassis with TT Motor N20G25
    - SUNLU High Speed PETG Filament 1.75mm Bundle, Less Stringing PETG 3D Printer Filament, 2kg in Total, 1kg per Spool, 2 Pack, Blue+Red
    - ZDF Lipo battery 3S 11.1V 5000mAh 6000mah 8000mah 10000mah 12000mah 16000mah 25C 30C 50C For RC Helicopter Quadcopter
    - GA12 N20 Encoder DC 6V Mini Micro Metal Gear DC Motor Gearwheel High Torque 15 25 50 70 100 150 300 500 1500RPM 7PPR Hall Sensor
    - 

