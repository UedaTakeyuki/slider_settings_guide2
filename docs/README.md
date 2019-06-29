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
<img src="./pic/ss.2019-06-29 14.33.04.png" width="50%">

Set 3G dongle on the USB port of the device.  
<img src="./pic/ss.2017-10-30 12.44.26.png" width="25%">

### Orange/Sonatel SIM Card
The software on the SD Card is preset for general **Orange/Sonatel** SIM card with following parameter.

- APN = internet
- Username = internet
- Password = internet

You **must** use SIM CARD with above parameters, or Network connection must NOT be start.


## Put SD Card on the device

Set "go" SD Card on the SD port of the device.  
<img src="./pic/ss.2017-10-30 12.44.36.png" width="25%">
<img src="./pic/ss.2017-10-30 12.44.45.png" width="25%">

## Turn on the device

Set Power supply micro USB cable.  
<img src="./pic/ss.2017-10-30 12.45.04.png" width="25%">
<img src="./pic/ss.2017-10-30 12.45.15.png" width="25%">
<img src="./pic/ss.2017-10-30 12.45.25.png" width="25%">

### LED Indicators on the device

Red and Green LED shoud be blinking. Red LED indicate power consumption, and Green indicate reading/writing to the SD card.
<img src="./pic/ss.2017-10-30 12.45.43.png" width="50%">

Because of Green indicate SD card access, it **must blink so busy** during system boot up, or **the SD card can't be accessed** from device due to **insufficient injection of the SD card**.  

In these case, once remove power supply micro USB cable, then push SD Card in again, and power supply micro USB cable again. 

In about a couple of minute, finally, GREEN led STAY turn on, and 3G dongle LED blink blue.  
<img src="./pic/ss.2017-10-30 12.45.57.png" width="50%">
<img src="./pic/ss.2017-10-30 12.45.57.png" width="50%">

### LED LED Indicator on the 3G dongle
#### ZTE-MF190
Red LED on the dongle indicate that power is supplied to it.  
<img src="./pic/ss.2019-06-29 15.09.30.png" width="25%">  
If LED is not turn on, it might be there are some trouble on the dongle.

Then soon LED turn on Green when dongle recognize there SIM card.   
<img src="./pic/ss.2019-06-28 22.13.34.png" width="25%">  
If LED is not turn on Green, it might be there are some trouble on the SIM CARD.  
  
Finally, it must be **blink** Green when network communication is started. If not, it must be that Operators network not reach to here, Operators account is not opend, or parameters of SIM CARD is not match with [expected](#orange-sonatel-sim-card).

## Q&A, issue report, feature request...
A forum for Q&A, issue report, feature request are available as follows:

[http://www.uedasoft.com/forums/forum/slider/](http://www.uedasoft.com/forums/forum/slider/)