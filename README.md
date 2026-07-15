# Our 2026 HackClub Fallout Project
Presented by Tyler Bergsma and Andy He (With a TON of CAD help from Keegan O'Neil)

## Our Project

We decided to make a Nerf Rival shooting mecanum-drive differential-turret robot that has auto aiming built in. This came from a love of robotics from all of us, and also because we all enjoy Nerf battles and guns.  Here's an example of what we wanted the turret to look initially: 

<img width="600" height="1600" alt="whatwewanted" src="https://github.com/user-attachments/assets/ba9f89c2-12f9-4298-b629-5825bec561df" />

This is what our original thought concept was considering the features we wanted for our bot.


The next most meaningful part of the robot is the drivetrain, which we decided would use mecanum wheels to give our robot incredibly diverse and versatile movement. Paired with the strong 600RPM motors we plan to use, this should give us a very snappy and responsive bot. 
Because our robot will be mostly 3d-printed out of PETG, it should be very durable, and the underlying frame (made of aluminum) brings that up even more.
Our camera system on the robot should also be extremely robust, using 3 cameras in total- 2 for general operator vision and 1 to give an onbaord raspberry pi access to auto-aiming features so that the robot can aim fully autonomously. We plan to send the camera input back to Tyler's Steamdeck OLED for processing and for human controller input. Speaking of sending information back and forth, the robot will use a 2.4Ghz WiFi adapter to connect to a local network and allow it to stream video and control signals back and forth. This gives us extremely low latency and high quality video, as well as the added benefit of being able to possibly be connected to LTE farther down the line and be controlled from anywhere in the world.
To shoot the Rival rounds, we plan to use two flywheels and shoot them around ~110-120fps in total, giving them some kick for a relatively short spin up time and a small amount of downtime per shot.

Here's a picture of our full 3D model (done in onshape), to show what we mean by all that:

<img width="592" height="541" alt="2026-06-16-220244_hyprshot" src="https://github.com/user-attachments/assets/1722e415-8795-4bc2-95e4-e08c2ae42fd5" />

<img width="528" height="468" alt="2026-06-16-220259_hyprshot" src="https://github.com/user-attachments/assets/2e71cdf1-ff3e-428a-ac19-04e0b3fada29" />

<img width="513" height="467" alt="2026-06-16-220311_hyprshot" src="https://github.com/user-attachments/assets/a008bc94-06e4-4e33-bdb3-273107c8feef" />

<img width="551" height="474" alt="2026-06-16-220324_hyprshot" src="https://github.com/user-attachments/assets/bed06d00-3843-4870-aea2-5569ef726d31" />

<img width="489" height="452" alt="2026-06-16-220334_hyprshot" src="https://github.com/user-attachments/assets/fa261901-55a5-4c6d-81fd-c8d24e3a47c1" />


CAD OnShape Link: https://cad.onshape.com/documents/071289950c39e2528783d758/w/1973af73cf652c9bb88bcb7f/e/c3e7d5f0022195b47dc63524


And here's a screenshot of the base chasis that we plan to use:

<img width="1112" height="940" alt="base chasis" src="https://github.com/user-attachments/assets/5f27916c-3c1b-4dcc-b199-ee658e77b5f5" />

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
| Quantity: 4 | Price: $8.38 | Total: $33.52
    - BTS7960 43A H-Bridge Motor Driver
| Quantity: 1 (4 pack) | Price: $24.89 | Total: $24.89
    - 60mm Mecanum Wheel Omnidirectional Wheel Smart Robot Car Chassis with TT Motor N20G25
| Quantity: 1 (4 pack) | Price: $9.48 | Total: $9.48
    - SUNLU High Speed PETG Filament 1.75mm Bundle, Less Stringing PETG 3D Printer Filament, 2kg in Total, 1kg per Spool, 2 Pack, Blue+Red
| Quantity: 1 (2kg) | Price: $25.64 | Total: $25.64
    - ZDF Lipo battery 3S 11.1V 5000mAh 6000mah 8000mah 10000mah 12000mah 16000mah 25C 30C 50C For RC Helicopter Quadcopter
| Quantity: 1 | Price: $46.69 | Total: $46.69
    - GA12 N20 Encoder DC 6V Mini Micro Metal Gear DC Motor Gearwheel High Torque 100 RPM 7PPR Hall Sensor
| Quantity: 3 | Price: $0.99 | Total: $2.79
    - Emax ECO II Series 2306 1700KV 1900KV 2400KV Brushless Motor for RC FPV Drone Racing Quadcopter Spare Parts RC Parts
| Quantity: 1 (2 pack) | Price: $25.46 | Total: $25.46
    - TB6612 DRV8833 Dual Motor Driver 1A TB6612FNG for Arduino Microcontroller Better than L298N
| Quantity: 1 (3 pack) | Price: $0.99 | Total: $0.99
    - LittleBee 20A 30A BLHeli-S ESC Support DSHOT OneShot For 2-6S FPV Quadcopter
| Quantity: 1 (4 pack) | Price: $31.62 | Total: $31.62

- Electronics
    - Raspberry Pi Zero 2 WH Kit
| Quantity: 1 | Price: $41.99 | Total: $41.99
    - Wi-Fi USB Dongle Adapter with Gain Antenna – Plug & Play for Linux (Tails, Ubuntu, Debian, Fedora, Mint, Arch) + Windows 11/10/8/7, Android & Mac | 2.4 GHz MT7601U Chipset 150 Mbps
| Quantity: 1 | Price: $17.99 | Total: $17.99
    - Arducam 5MP Camera for Raspberry Pi, 1080P HD OV5647 Camera Module V1 for Raspberry Pi5/4/3/3B+, and Other A/B Series
| Quantity: 1 (maybe 2-4) | Price: $6.99 | Total: $6.99
    - ESP32-CAM WiFi Module 2.4G Antenna ESP32 Serial to WiFi ESP32 CAM Development Board 5V Bluetooth with OV3660 / OV2640 Camera DIY
| Quantity: 2 | Price: $6.46 | Total: $12.92
    - Official Raspberry Pi Pico Board RP2040 Dual-Core 264KB ARM Low-Power Microcomputers High-Performance Cortex-M0+ Processor
| Quantity: 3 | Price: $0.99 | Total: $2.79
    - 1-10pcs PCA9685PW 16 Channel 12-Bit PWM Servo Shield Driver I2C Interface PCA9685 Module For Raspberry Pi
| Quantity: 1 | Price: $0.99 | Total: $0.99
    - 2-8PCS LM2596 Step-down Power Supply Module 3A 3.2V-46V DC to DC Voltage Regulator Module Buck Converter Power Supply Modules
| Quantity: 1 (4 pack) | Price: $9.26 | Total: $9.26
    - AC 220V 250RPM 300RPM 6 Channel 6 wires Capsule Slip Ring CIRCUITSx2A Slipring 12.5/22MM Mini Rotary Conductive Joint Connectors
| Quantity: 1 | Price: $0.99 | Total: $0.99
    - 14AWG XT60 Female Male Plug Battery Connector with Silicone Flexible Wire for RC Airplane Lipo Battery ESC FPV Drone Car Boat | Quantity: 1 (10 pack)
| Price: $12.50 | Total: $12.50
    - 5 Colors Flexible Silicone Wire 16 AWG Gauge Tinned Copper Stranded Wire 300V Cables Electronic Wire Cable
| Quantity: 1 (5 colors, 4 meters) | Price: $9.30 | Total: $9.30
    - 5 Colors Flexible Silicone Wire 22 AWG Gauge Tinned Copper Stranded Wire 300V Cables Electronic Wire Cable
| Quantity: 1 (5 colors, 10 meters) | Price: $0.99 | Total: $0.99

- Others
    - 25V DIP Aluminum Electrolytic Capacitor 100UF
| Quantity: 1 (40 pack) | Price: $0.99 | Total: $0.99
    - POKONBOY 300 Rounds Refill Pack Balls Ammo Compatible with Nerf Rival Gun, Foam Bullet Ball Replacement Refill Pack for Blasters Guns
| Quantity: 1 (300 count) | Price: $24.99 | Total: $24.99
    - 0.5" Hex Shaft Collars
| Quantity: 5 | Price: $2.99 | Total: $14.95
    - 0.500" Hex ID x 1.125" OD x 0.313" WD (Flanged Bearing) (WCP-0783)
| Quantity: 4 | Price: $2.99 | Total: $11.96
    - OV2640 160 degrees 850nm night version 940nm camera module 21MM 24PIN 0.5MM spacing
| Quantity: 1 | Price: $0.99 | Total: $0.99
    - 10/50pcs Small Bearings 2mm 3mm 4mm 5mm 6mm 7mm 8mm 9mm 10mm Bore 3x7x3 5x10x4 5x11x4 8x22x7 10x15x4 mm Miniature Bearing
| Quantity: 20 (10 8x12x3.5mm and 10 15x21x4mm| Price: $0.99 | Total: $0.99
    - 5Pcs 6903RS 12x28x8mm Motor Grade Cover Sealed Deep Groove Ball Bearing RS 52100 Chrome Steel ABEC-7
| Quantity: 1 (5 pack 6903RS 17x30x7) | Price: $0.99 | Total: $0.99
    - 1/2in Rounded Hex Shafts
| Quantity: 1 | Price: $10.50 | Total: $10.50
    - 4Pcs 6mm Coupling
| Quantity: 1 (4 pack) | Price: $0.82 | Total: $0.82

Total Cost: $382.41

## Zine Page
<img width="1398" height="2000" alt="Turret Bot Zine Page (1)" src="https://github.com/user-attachments/assets/25b177a6-ee11-444b-aaf1-6ed932c90da0" />

## How to Replicate and Understanding

Ratios:
Base Differential gears: 5:1or 125:25
Internal to external: 102:27 or 34/9:1
Bevel gears: 1:1 or 20:20
Angle control: 100:16 or 6.25:1

coaxial/differential explanation:
The differential turret consists of two base gears, with one gear having only external teeth, and the other having both external and internal teeth. A separate gear is mounted to the gear that only has external teeth, but it is driven by the gear that has both internal and external gears. The gear that gets driven internally directly drives a bevel gear. This bevel gear drives another bevel gear that is mounted to a shaft that is mounted on the base gear with only external teeth. Also mounted on that shaft is two normal spur gears that end up driving the turret that is also mounted on the base gear with only external teeth. 

Turret:
The turret consists of a camera for object detection and auto aiming with the coaxial gear system, two flywheels that are directly driven by brushless motors, an agitation motor and wheel to prevent jams, and a hopper to hold bullets. The bullets that the hopper holds feed into a square funnel that also leads into a rectangular funnel shouldn’t jam due to an agitation motor. The rectangular funnel feeds into a single stream that is prevented from getting jams due to the flywheel also acting as an agitation wheel. These bullets eventually feed through into the flywheels, which have 0.175 inches of compression on the bullets, to eventually get shot at a specific target.

How to replicate:
For the overall robot, you will want to determine all the electronic and mechanical components you will be using, then determine where and how you want them mounted. For the drive base, you will want to figure out what kind of driving system you want to use (mecanum, swerve, or something else), then create a master sketch of the side view and the top view of how you want the overall layout to look. The group decided that our shooting mechanism would be a coaxial turret, and that we would be using mecanum wheels to drive the robot so we could get omnidirectional mobility. Once you have your overall design picked and drawn out, you should start out with the drivetrain, which you will design around the parts list and the master sketch. For your drivetrain, you will need to mount out where all the electronics and maybe some mechanical things will be located/mounted and how they will be mounted so you need to create space for that. This includes things such as your motors, the overall brain potentially, wire management, battery, motor controllers, buck converters, cameras, wheels, and much more. We personally decided to mount all electronics other than 3 motors, pi cam, and the pi zero, which we mounted to the turret itself. The pi zero and camera serve as components directly linked object detection cam and brain and the motors control the flywheels. Once you have the method for mounting everything, and you have the overall design finished for the drivetrain, you can move on to the shooter. As previously stated, we went with a coaxial turret. To start out, decide what ratios and tooth counts you want for the gears driving the turret angle and position. We used a 5:1 for each base gear. You will also want to determine how you will feed the shooter itself. We went with a funnel indexing system that had 2 points of agitation to prevent jamming. You will also need to keep in mind the assembly. I would have run into a bunch of assembly errors if I hadn’t triple checked my work, so be careful about that. Finally, once you have the drivetrain and turret mechanism figured out, you can add tolerances and put it all together into an assembly to make sure everything packages without any problems.

