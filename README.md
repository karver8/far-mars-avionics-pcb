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
| Component/Part Name               	| Link/Part Number                                                                                                                                 	| Vendor   	| Qty Per Brd 	|
|-----------------------------------	|--------------------------------------------------------------------------------------------------------------------------------------------------	|----------	|-------------	|
| SAMD21G18 Microcontroller         	| [1611-ATSAMD21G18A-AFTCT-ND](https://www.digikey.com/product-detail/en/microchip-technology/ATSAMD21G18A-AFT/1611-ATSAMD21G18A-AFTCT-ND/6832839) 	| Digi-Key 	| 1           	|
| BNO055 IMU                        	| [828-1058-1-ND](https://www.digikey.com/product-detail/en/bosch-sensortec/BNO055/828-1058-1-ND/6136309)                                          	| Digi-Key 	| 1           	|
| SN65HVD32DR 485 Transciever       	| [296-19627-1-ND](https://www.digikey.com/product-detail/en/texas-instruments/SN65HVD32DR/296-19627-1-ND/1016501)                                 	| Digi-Key 	| 1           	|
| Molex microSD Slot                	| [WM12834CT-ND](https://www.digikey.com/product-detail/en/molex-llc/5031821852/WM12834CT-ND/5823232)                                              	| Digi-Key 	| 1           	|
| SWD Debugger Header               	| [S9015E-05-ND](https://www.digikey.com/product-detail/en/sullins-connector-solutions/GRPB052VWVN-RC/S9015E-05-ND/1786455)                        	| Digi-Key 	| 1           	|
| PWR Switch                        	| [EG1903-ND](https://www.digikey.com/product-detail/en/e-switch/EG1218/EG1903-ND/101726)                                                          	| Digi-Key 	| 1           	|
| SM Config Switch                  	| [401-2013-1-ND](https://www.digikey.com/product-detail/en/c-k/AYZ0202AGRLC/401-2013-1-ND/1640122)                                                	| Digi-Key 	| 1           	|
| TPS62162 3.3V Reg                 	| [296-45272-1-ND](https://www.digikey.com/product-detail/en/texas-instruments/TPS62162QDSGRQ1/296-45272-1-ND/6597316)                             	| Digi-Key 	| 1           	|
| 0603 100nF Capacitor 16V rated    	| [311-1776-1-ND](https://www.digikey.com/product-detail/en/yageo/CC0603JRX7R7BB104/311-1776-1-ND/5195678)                                         	| Digi-Key 	| 7           	|
| 0603 6.8nF Capacitor 16V rated    	| [587-1089-1-ND](https://www.digikey.com/product-detail/en/taiyo-yuden/EMK107SD682JA-T/587-1089-1-ND/930866)                                      	| Digi-Key 	| 1           	|
| 0603 22uF Capacitor 16V rated     	| [1276-7076-1-ND](https://www.digikey.com/product-detail/en/samsung-electro-mechanics/CL10A226MO7JZNC/1276-7076-1-ND/7320718)                     	| Digi-Key 	| 1           	|
| 0603 10uF Capacitor 16V  rated    	| [490-12736-1-ND](https://www.digikey.com/product-detail/en/murata-electronics-north-america/GRM188R61C106KAALJ/490-12736-1-ND/5797705)           	| Digi-Key 	| 1           	|
| 0806 2.2uH Inductor 1A+ sat/rated 	| [SRP2010-2R2MCT-ND](https://www.digikey.com/product-detail/en/bourns-inc/SRP2010-2R2M/SRP2010-2R2MCT-ND/4876863)                                 	| Digi-Key 	| 1           	|
| 0603 Red LED 2V/20mA              	| [475-2512-1-ND](https://www.digikey.com/product-detail/en/osram-opto-semiconductors-inc/LS-Q976-NR-1/475-2512-1-ND/1802639)                      	| Digi-Key 	| 1           	|
| 0603 Green LED 2V/20mA            	| [160-1446-1-ND](https://www.digikey.com/product-detail/en/lite-on-inc/LTST-C191KGKT/160-1446-1-ND/386834)                                        	| Digi-Key 	| 1           	|
| 0805 Filter for AREF              	| [MH2029-300YCT-ND](https://www.digikey.com/product-detail/en/bourns-inc/MH2029-300Y/MH2029-300YCT-ND/3741761)                                    	| Digi-Key 	| 1           	|
| 0603 100k Resistor LT             	| [A106046CT-ND](https://www.digikey.com/product-detail/en/te-connectivity-passive-product/CRG0603F100K/A106046CT-ND/3477684)                      	| Digi-Key 	| 1           	|
| 0603 10k Resistor                 	| [A106048CT-ND](https://www.digikey.com/product-detail/en/te-connectivity-passive-product/CRG0603F10K/A106048CT-ND/3477687)                       	| Digi-Key 	| 6           	|
| 0603 1.6k Resistor LT             	| [P1.6KBECT-ND](https://www.digikey.com/product-detail/en/panasonic-electronic-components/ERA-3ARW162V/P1.6KBECT-ND/3073304)                      	| Digi-Key 	| 5           	|
| 0603 3.3k Resistor LT             	| [RG16N3.3KWCT-ND](https://www.digikey.com/product-detail/en/susumu/RG1608N-332-W-T1/RG16N3.3KWCT-ND/600797)                                      	| Digi-Key 	| 5           	|
| 0603 64.9 Resistor LT             	| [311-64.9HRCT-ND](https://www.digikey.com/product-detail/en/yageo/RC0603FR-0764R9L/311-64.9HRCT-ND/730290)                                       	| Digi-Key 	| 2           	|
| 0603 1k Resistor                  	| [311-1.00KHRCT-ND](https://www.digikey.com/product-detail/en/yageo/RC0603FR-071KL/311-1.00KHRCT-ND/729790)                                       	| Digi-Key 	| 2           	|
