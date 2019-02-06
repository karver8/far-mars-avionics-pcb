# far-mars-avionics-controller

![](https://raw.githubusercontent.com/SDSURocketProject/far-mars-avionics-pcb/master/images/header.png)

The **far-mars-avionics-controller** is a custom built printed circuit board that performs data aquisition, logging, and communication, all in one highly power effecient, light weight, and compact design. This circuit was built around the FAR/MARS rocket competition, which challenges teams to design a LOX/Methane rocket to accuractley target an altitude of 45,000 feet.

### Features
* ARM Cortex M0+ microcontroller
* 9 multi-purpose I/O pins (+1 DIO PIN)
* Up to 9 12bit and 2 16bit Analog to Digital channels.
* RS-485 Transciever for long distance LVDS ground communications
* CANbus Transciever for future feature expansion
* BNO055 Inertial Measurement Unit
* Locking microSD card slot for secure, vibration resistant data logging
* 5-17V Input Range allowing for versatile power supply.
* Power Effecient enabling the use of a tiny battery
* Very light, weighs less than an ounce of feathers!
* Built-in battery charge monitoring.
* Highly accurate crystal for detailed timestamping.

### Firmware

The FAR/MARS rocket uses a FreeRTOS implementation to safley and predictabley manage the various avionics tasks required to launch the rocket. Documentation and development of the firmware for this board can be found in our [far-mars-onboard-firmware](https://github.com/SDSURocketProject/far-mars-onboard-firmware) repository. 

### Documentation
Here is everything you need to interface with this PCB and/or to write your own drivers and firmware:
* far-mars-avionics-controller Datasheet
* [Pinout](https://github.com/SDSURocketProject/far-mars-avionics-pcb/blob/master/documentation/pinout.pdf "Pinout")
* Electrical Specifications
* [Device Datasheet Collection](https://github.com/SDSURocketProject/far-mars-avionics-pcb/tree/master/documentation/Datasheets "Device Datasheet Collection")
* Development Notes

### Assembly
We highly recommend that you outsource the assembly of this PCB. This design has a lot of tiny surface mount components, on both sides of the board, so unless you have experience reflowing on two sides, this will be almost impossible to assemble yourself. We used MacroFab for the most recent version of this PCB. The current BOM is also optimized to take advantage of their 10-day turnaround service. Here is everything you need to assemble your own avionics controller:
* [Bill of Materials](https://github.com/SDSURocketProject/far-mars-avionics-pcb/tree/master/assembly/BOM#bill-of-materials "Bill of Materials")
* [Gerber Files](https://github.com/SDSURocketProject/far-mars-avionics-pcb/tree/master/assembly/Gerbers)
* [Instructions](https://github.com/SDSURocketProject/far-mars-avionics-pcb/tree/master/assembly#assembly-guide "Instructions")
* [Design Slides](https://github.com/SDSURocketProject/far-mars-avionics-pcb/blob/master/assembly/Physical%20Summary.pdf "Physical Summary")
* **Schematic & Layout Files are in the top directory**

