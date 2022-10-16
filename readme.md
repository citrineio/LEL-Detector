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
