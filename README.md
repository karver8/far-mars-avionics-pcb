# far-mars-barebones-pcb

**CAUTION: THIS BOARD IS STILL IN DEVELOPMENT, MATERIALS AND DESIGN UNTESTED**


Variation of the [far-mars-dpm-pcb](https://github.com/SDSURocketProject/far-mars-dpm-pcb) without Dynamic Power Managment
* ARM Cortex M0+ Based Microcontroller
* 5 Analog to Digital Converters
* MicroSD card slot logging telemetry
* Miscellaneous digital i/o ports for reading rocket states and futureproofing
* RS-485 transciever for long distance wired communication
* BNO055 Inertial Measurement Unit
* Small size and power efficient 


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

## Recommended Headers and Housings 

| Component/Part Name           	| Link/Part Number                                                                                          	| Vendor   	| Qty Per Brd 	|
|-------------------------------	|-----------------------------------------------------------------------------------------------------------	|----------	|-------------	|
| 8x1 Male FL Header            	| [609-1310-ND](https://www.digikey.com/product-detail/en/amphenol-fci/76384-308LF/609-1310-ND/1001624)     	| Digi-Key 	| 1           	|
| 8x1 Female FL Housing         	| [609-1268-ND](https://www.digikey.com/product-detail/en/amphenol-fci/65240-008LF/609-1268-ND/1001582)     	| Digi-Key 	| 1           	|
| 4x1 Male Friction Lock Header 	| [609-1306-ND](https://www.digikey.com/product-detail/en/amphenol-fci/76384-304LF/609-1306-ND/1001620)     	| Digi-Key 	| 1           	|
| 4x1 Female FL Housing         	| [609-1264-ND](https://www.digikey.com/product-detail/en/amphenol-fci/65240-004LF/609-1264-ND/1001578)     	| Digi-Key 	| 1           	|
| 2x1 Male Friction Lock Header 	| [609-1304-ND](https://www.digikey.com/product-detail/en/amphenol-fci/76384-302LF/609-1304-ND/1001618)     	| Digi-Key 	| 3           	|
| 2x1 Female FL Housing         	| [609-1262-ND](https://www.digikey.com/product-detail/en/amphenol-fci/65240-002LF/609-1262-ND/1001576)     	| Digi-Key 	| 3           	|
| 5x1 Male Friction Lock Header 	| [609-1307-ND](https://www.digikey.com/product-detail/en/amphenol-fci/76384-305LF/609-1307-ND/1001621)     	| Digi-Key 	| 1           	|
| 5x1 Female FL Housing         	| [609-1265-ND](https://www.digikey.com/product-detail/en/amphenol-fci/65240-005LF/609-1265-ND/1001579)     	| Digi-Key 	| 1           	|
| Compatible Crimp Heads        	| [609-3055-1-ND](https://www.digikey.com/product-detail/en/amphenol-fci/76347-301LF/609-3055-1-ND/1642308) 	| Digi-Key 	| 25          	|

## Recommended Miscellaneous

| Component/Part Name 	| Link/Part Number                                                                                                                                                                                                    	| Vendor   	| Qty Per Brd 	|
|---------------------	|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|----------	|-------------	|
| Atmel ICE Debugger  	| [ATATMEL-ICE-ND](https://www.digikey.com/product-detail/en/microchip-technology/ATATMEL-ICE/ATATMEL-ICE-ND/4753379)                                                                                                 	| Digi-Key 	| N/A         	|
| Reflow Skillet      	| [CKSTSKFM12W-ECO](https://www.amazon.com/Oster-CKSTSKFM12W-ECO-DuraCeramic-Electric-Skillet/dp/B00ESF08JQ)                                                                                                          	| Amazon   	| N/A         	|
| Nylon Spacers       	| [RPC4978-ND](https://www.digikey.com/products/en/hardware-fasteners-accessories/washers/571?k=&pkeyword=&pv147=565&FV=1180006%2Cffe0023b%2Cc1c011a&mnonly=0&ColumnSort=0&page=1&quantity=0&ptm=0&fid=0&pageSize=25) 	| Digi-Key 	| 8           	|
| Soldering Stencil   	| N/A                                                                                                                                                                                                                 	| N/A      	| N/A         	|
