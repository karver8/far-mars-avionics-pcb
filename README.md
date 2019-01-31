# far-mars-avionics-controller

![](https://raw.githubusercontent.com/SDSURocketProject/far-mars-avionics-pcb/master/images/header.png)

The **far-mars-avionics-controller** is a custom built printed circuit board that performs data aquisition, logging, and communication, all in one highly power effecient, light weight, and compact design. This circuit was built around the FAR/MARS rocket competition, which challenges teams to design a LOX/Methane rocket to accuractley target an altitude of 45,000 feet.

### Features
* ARM Cortex M0+ microcontroller
* 9 multi-purpose I/O pins (+1 DIO PIN)
* Up to 9 12bit and 2 16bit Analog to Digital readings.
* RS-485 Transciever for long distance LVDS ground communications.
* CANbus Transciever for a more modular design.
* BNO055 Inertial Measurement Unit for data acquisition.
* Locking microSD card slot for data logging.
* 5-17V Power Supply so you can power everything off of one battery.
* Power Effecient enabling the use of a very small LiPo.
* Very small, weighs less than an ounce!
* Onboard battery charge measurement.
* Highly accruate crystal for fine measurements.

### Firmware

The FAR/MARS rocket uses a FreeRTOS implementation to safley and predictabley manage the various avionics tasks required to launch the rocket. Documentation and development of the firmware for this board can be found in our [far-mars-onboard-firmware](https://github.com/SDSURocketProject/far-mars-onboard-firmware) repository. 

### Documentation
Here is everything you need to know to interact with this PCB and/or to write your own drivers and firmware.
* far-mars-avionics-controller Datasheet
* Pinout
* Errata
* Device Datasheet Collection
* Development Notes

### Assembly
We highly recommend that you outsource the assembly of the PCB. This design has a lot of tiny surface mount components, on both sides of the board, so unless you have experience reflowing on two sides this will be an almost impossble to assemble yourself. We used MacroFab for the most recent version of this PCB. The current BOM is also optimized to take advantage of their 10-day turnaround service.
#####Assembly Resources
* Bill of Materials
* Eagle Libraries
* Physical Summary
                                                                                                                                                                                                            	| N/A      	| N/A         	|
