# Boost-Conv-TL494-250W
 A step-up circuit which convert voltage to higher value with peak power of 250W

It converts 9-48V to a maximum of 48V (Depends on capacitor and MOSFET voltage rating), the output power is rated at 250W but effectively limited by the max input current of 10A. The efficiency is about 85-95%.

It is based on **TL494 Pulse-Width-Modulation Control Circuits**

## Features / Specs

* Module Type: DC-DC Boost / Step-Up Converter (Non-isolated)
* Output Regulation Modes: Constant Current / Constant Voltage
* Input Voltage: 8.5 – 48VDC
* Output Voltage: 10 – 50VDC
* Input Current: 10A (Max) (If input current is greater than 8A extra cooling is   required)
* Constant Current Range: 0.2A – 8A
* Conversion Efficiency: Up tp 95%
* Switching Frequency: 150kHz
* Over-current and reverse polarity protection
* Operating Temperature: -40℃ to +85℃

**(This circuit can be fabricated in home a printable file is attached in PCB folder.)**

There are 2 version of the design one with SMD vesion of TL494 IC and the other with through hole version, **I recommend the TH version as has better heat disspation for the MOSFET and the schottky diode**.

## DIY Sample
### SMD Version
![](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Photos/IMG_1.jpg?raw=true)
![](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Photos/IMG_4.jpg?raw=true)

### TH Version
![](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Photos/IMG_5.jpg?raw=true)
![](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Photos/IMG_6.jpg?raw=true)
![](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Photos/IMG_8.jpg?raw=true)

**NOTE:** The power Lines is recommended to be strengthened by solder.
 (The copper was over etched by acid in this samble :sweat_smile:, but this problem was fixed in the next samble in blue UV-mask )

![](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Photos/IMG_9.jpg?raw=true)

## Schematic
![Schematic](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Schematic/Boost_Conv_SMD_TL494_250W_Sch.png?raw=true)

## 2D PCB
### SMD Version
![2D PCB](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/PCB/2D-Top.png?raw=true)

### TH Version
![2D PCB](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/PCB/2D-Top_TH.png?raw=true)
**NOTE:** The bottom connection are jumper wires.

## 3D PCB
### SMD Version
![3D PCB](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/PCB/3D-Top.png?raw=true)


### TH Version
![3D PCB](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/PCB/3D-Top_TH.png?raw=true)
![3D PCB](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/PCB/3D-Bot.png?raw=true)


### The design inspired by the following Chinese kit:
![](https://github.com/AhmedHafez2000/Boost-Conv-TL494-250W/blob/main/Photos/IMG_0.jpg?raw=true)