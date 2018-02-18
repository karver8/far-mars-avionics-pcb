# far-mars-barebones-pcb

**CAUTION: THIS BOARD IS STILL IN DEVELOPMENT, MATERIALS AND DESIGN UNTESTED**


Variation of the [far-mars-dpm-pcb](https://github.com/SDSURocketProject/far-mars-dpm-pcb) without Dynamic Power Managment
* Cortex M0 Based Microcontroller
* Analog to Digital Converters for Pressure Data
* MicroSD for data logging
* Miscellaneous GPIO ports for reading rocket states and futureproofing
* RS-485 interface for long distance wired communications
* High Sample Rate Inertial Measurment Unit
* Purpose Built and Highly Power Effecient


## The Board

![](https://github.com/SDSURocketProject/far-mars-barebones-pcb/blob/master/renders/info.png  "Render provided by OSHpark")

## Firmware

Documentation and development of the firmware for this board can be found in our [far-mars-onboard-firmware](https://github.com/SDSURocketProject/far-mars-onboard-firmware) repository.

## Bill of Materials

| Component/Part Name               | Link/Part Number      | Vendor   | Qty Per Brd |
|-----------------------------------|-----------------------|----------|-------------|
| SAMD21G18 Microcontroller         | ATSAMD21G18A-AFTCT-ND | Digi-Key | 1           |
| BNO055 IMU                        | 828-1058-1-ND         | Digi-Key | 1           |
| SN65HVD32DR 485 Transciever       | 296-19627-1-ND        | Digi-Key | 1           |
| Molex microSD Slot                | WM12834CT-ND          | Digi-Key | 1           |
| SWD Debugger Header               | S9015E-05-ND          | Digi-Key | 1           |
| PWR Switch                        | EG1903-ND             | Digi-Key | 1           |
| SM Config Switch                  | 401-2013-1-ND         | Digi-Key | 1           |
| TPS62162 3.3V Reg                 | 296-45272-1-ND        | Digi-Key | 1           |
| 0603 100nF Capacitor 16V rated    | 311-1776-1-ND         | Digi-Key | 7           |
| 0603 6.8nF Capacitor 16V rated    | 587-1089-1-ND         | Digi-Key | 1           |
| 0603 22uF Capacitor 16V rated     | 1276-7076-1-ND        | Digi-Key | 1           |
| 0603 10uF Capacitor 16V  rated    | 490-12736-1-ND        | Digi-Key | 1           |
| 0806 2.2uH Inductor 1A+ sat/rated | SRP2010-2R2MCT-ND     | Digi-Key | 1           |
| 0603 Red LED 2V/20mA              | 475-2512-1-ND         | Digi-Key | 1           |
| 0603 Green LED 2V/20mA            | 160-1446-1-ND         | Digi-Key | 1           |
| 0805 Filter for AREF              | MH2029-300YCT-ND      | Digi-Key | 1           |
| 0603 100k Resistor LT             | A106046CT-ND          | Digi-Key | 1           |
| 0603 10k Resistor                 | A106048CT-ND          | Digi-Key | 6           |
| 0603 1.6k Resistor LT             | P1.6KBECT-ND          | Digi-Key | 5           |
| 0603 3.3k Resistor LT             | RG16N3.3KWCT-ND       | Digi-Key | 5           |
| 0603 64.9 Resistor LT             | 311-64.9HRCT-ND       | Digi-Key | 2           |
| 0603 1k Resistor                  | 311-1.00KHRCT-ND      | Digi-Key | 2           |
