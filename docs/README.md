## Introduction

This document introduce the step of how to start the SLIDER, a IoT remote sensing device developed at Atelier UEDA.

## Put 3G Dongle on the device
### ZTE-MF190 dongle
<img src="./pic/ss.2019-06-28 22.06.38.png" width="25%">

Open the Cap.  
<img src="./pic/ss.2019-06-28 22.13.16.png" width="25%">


Open body cover as follow:  

Hook your nail to the notch on the top.  
<img src="./pic/ss.2019-06-28 22.14.34.png" width="50%">  
Then tear off it.  
<img src="./pic/ss.2019-06-28 22.14.22.png" width="50%">


Set SIM card. Make sure the posion of the "lack Corner" is same as the "printed indicate".  
<img src="./pic/ss.2017-10-30 12.43.57.png" width="50%">
<img src="./pic/ss.2017-10-30 12.44.15.png" width="50%">

Set 3G dongle on the USB port of the device.  
<img src="./pic/ss.2017-10-30 12.44.26.png" width="25%">

### Orange/Sonatel SIM Card
The software on the SD Card is preset for general **Orange/Sonatel** SIM card with following parameter.

- APN = internet
- Username = internet
- Password = internet

You **must** use SIM CARD with above parameters, or Network connection must not be start.


## Put SD Card on the device]

Set "go" SD Card on the SD port of the device.  
<img src="./pic/ss.2017-10-30 12.44.36.png" width="25%">
<img src="./pic/ss.2017-10-30 12.44.45.png" width="25%">

## Turn on the device]

Set Power supply micro USB cable.  
<img src="./pic/ss.2017-10-30 12.45.04.png" width="25%">
<img src="./pic/ss.2017-10-30 12.45.15.png" width="25%">
<img src="./pic/ss.2017-10-30 12.45.25.png" width="25%">


Red and Green LED shoud be blinking. Red LED indicate power consumption, and Green indicate reading/writing to the SD card.
<img src="./pic/ss.2017-10-30 12.45.43.png" width="50%">

Because of Green indicate SD card access, it **must blink so busy** during system boot up, or **the SD card can't be accessed** from device due to **insufficient injection of the SD card**.  

In these case, once remove power supply micro USB cable, then push SD Card in again, and power supply micro USB cable again. 

In about a couple of minute, finally, GREEN led STAY turn on, and 3G dongle LED blink blue.  
<img src="./pic/ss.2017-10-30 12.45.57.png" width="50%">
<img src="./pic/ss.2017-10-30 12.46.14.png" width="25%">