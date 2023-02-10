# OpenPLC-IIoTv0.1 (Industrial Internet of Things)

![3D Generado por Kicad](PCB_Jose_Laica/Vista3D/PLC32V01_kicad.png)

> We seek to encourage the technological community to collaboratively develop new platforms for the industry under the philosophy of free hardware and software. Building a programmable logic controller based on the ESP32 microcontroller and programmed with Micropython.

## About the PROJECT
PLCs (Programmable Logic Controller) are currently used in all types of industrial applications, solving requirements in process control and machinery sequences, within the industrial sector in processes and control of industrial robotic arms.


### Short-term goals for our project

Integrate students, professionals, and people for purposes of technology through the development of projects in a collaborative way, so that they can exchange knowledge, learn, and develop together.

### Long-term goals for our project

The community, individually or as an association, can improve and modify these projects so that they can be offered locally with the quality that the industry requires.

### Methodology

This is a collaborative project so any external person can collaborate, including the attendees of the meetings. This will develop through PRs to either the main repo or their own forked repos.

We will tentatively meet every Thurday to advance the development of this project as a group.




## Features for PLC hardware

Hardware     | Specification
:---------------------------| :-------
Power Supply     | 24 volts DC 
Digital Input |2, 24 volts
Digital Outputs	| NPN open collector (current sink) outputs of 200mA each.
Analog Inputs | 0
Communications	| 1 × USB port, 1 × RS-485 port, 1 x Integrated Wifi : Access point & Station, 1 x Bluetooth 4.2 2.4 Ghz; BT 2.0 and 4.0 BLE. 
Memory | ROM: 448 KiB; for booting and core functions, SRAM: 520 KiB; For data and instruction, RTC fast SRAM: 8 KiB; For data storage and main CPU during RTC Boot from the deep-sleep mode, RTC slow SRAM: 8 KiB; For co-processor accessing during deep-sleep mode, eFuse: 1 Kibit; are used for the system (MAC address and chip configuration).
Microcontroller | Dual Core Xtensa® LX6 32-bit Processor, 240 Mhz, 36 GPIO pins, 16 x Analog-to-Digital Converter (ADC) with 12 bit resolution and can be programmed with input limit at 1V, 2V, and 4V, 2 x Digital to Analog converter 8-bit DAC, Up to 16 PWM channels can be defined, 2 x UART or serial ports, 2 x I2C channels and 4 x SPI channels, Integrated Wifi: Access point & Station, 1 x Bluetooth 4.2 2.4 Ghz; BT 2.0 and 4.0 BLE
Mounting | Uses standard DIN rail for mounting
Programming | Code is uploaded via a micro-USB port


## Workshops
We will develop the project through various workshops 

1.- Design of the PCB card

Issue             |Instructor | Place | Date | Schedule
-----------------|-----------|-------|-------|--------
Introduction to PLC stages |José Laica | Mobile Robotics Laboratory - ESPOL | November 21, 2019 | 13:30 - 15:30
Open Source ECAD tools |José Laica | Mobile Robotics Laboratory - ESPOL | December 5, 2019 | 13:30 - 15:30
Schematic design of the PLC stages |José Laica | Mobile Robotics Laboratory - ESPOL | December 12, 2019 | 13:30 - 15:30
Open source ECAD tools for PCB design |José Laica | Mobile Robotics Laboratory - ESPOL | January 9, 2020 | 13:30 - 15:30 
Development of the print circuit board |José Laica | Mobile Robotics Laboratory - ESPOL | January 16, 2020 | 13:30 - 15:30 

- Tools to use: https://easyeda.com/es

- Schematics obtained:
https://easyeda.com/jlaica/openplc32-iiot_copy

![Imagen generada en easy eda](/PCB_Jose_Laica/esquematicos/Salidas.png)

2.- 3D modeling for the casing design from a PCB with FreeCAD

Instructor | Place | Date | Schedule
-----------|-------|-------|--------
Christian Tayupanta | ESPOL | January 6, 2020 | 13:30 - 16:30

- FreeCAD link:: https://www.freecadweb.org

- PCB model used: 
https://github.com/FunPythonEC/PLC32/tree/master/Modelo3D_PCB

3.- Assembling the PCB and programming the MicroPython firmware

Instructor | Place | Date | Schedule
-----------|-------|-------|--------
FunPython | Mechatronics Laboratory - ESPOL | February 17, 2020 | 10:00 - 15:00

[Registration Link](http://bit.ly/plc32fpy)

![Invitacion](media/flyer_PLC32_PCB.jpeg)

4.- Development of the programming environment for the PLC32, based on Drag-and-Drop blocks.

Instructor | Place | Date | Schedule
-----------|-------|-------|--------
TBD | TBD | February 2020 | Evening



## Registration

[For registration updates](https://docs.google.com/forms/d/e/1FAIpQLSdKHHjlvKSSVwDHgesz2nPQxdpG3-TAMdvfw-ti1jtBzHu5PQ/viewform)

## Slack

[Channel: plc32_hardware ](https://app.slack.com/client/TRBPLJYKT/CRMJ3G1T6)


## Contact
For talks or workshops contact:

### Email

funpython.ec@gmail.com 

### Socials

[Instagram](https://www.instagram.com/funpython/)
[Twitter](https://twitter.com/funpython_ec)
[Linkedin](https://www.linkedin.com/company/funpython)

