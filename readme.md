# Project Description

This project takes inspiration from my current job as a control and instrumentation engineer in the oil and gas industry. We have to deal with the risk of combustible or toxic gases leaks and one of the mandatory protection mechanisms is having a gas detection system. I designed a detector for combustible gases especially H2 which utilizes a common communication protocol to send data to the main controller in the system. 

This project incorporates the following: 
- SGP30 air quality sensor with H2 detection capability
- STM32F103 microcontroller
- LTC2631ITS8 I2C DAC with voltage output
- AD5749 4-20mA transmitter IC to send data to a connector and then to the control system.
- AOM12864A0 1.54" OLED display for reading the sensor's value.
- Two Omron relays for controlling and signaling an alarm light and a horn during a gas leak.

## Block Diagram

![Block Diagram](https://user-images.githubusercontent.com/71399691/196049351-8af7a224-e577-4999-854c-2059e4e5a7d0.jpg)

## Board Images

![LEL Detector Nice ](https://user-images.githubusercontent.com/71399691/196050011-fba6fb54-3544-4988-93b3-46cdcc803abd.jpg)

![LEL Detector](https://user-images.githubusercontent.com/71399691/196050020-7f369ce2-1a90-4e75-aa05-27d5c61337ae.jpg)

![LEL Detector back ](https://user-images.githubusercontent.com/71399691/196050032-1eafafcb-c521-4b27-8a59-2ccf92db90e6.jpg)

## Repository Guide:

### 3D:

3D model of the PCB, 3D models of the components are also available in the dedicated folder.

### Datasheets:

This is where you can access the datasheets of the major components used in the design. The readme file contains the rules for suggesting components and uploading datasheets. 

Suggesting components and ensuring that the uploaded datasheets are up to date will be a big help for us.

### PCB Layout: 

The latest Kicad PCB layout file is here. You can find component land patterns (aka footprints) in the dedicated folder.

### Schematics:

The latest Kicad schematics capture files are here. PDF version will be updated weekly during the schematics capture phase. You can also find the schematics symbols in the dedicated folder. 

