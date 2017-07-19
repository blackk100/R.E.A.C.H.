<!-- Uses GitHub Flavoured Markdown-->

# R.E.A.C.H. Generic Electronics Part List

 All costs are as of 19:00, 19th July, 2017 IST.

 All costs are exclusive of taxes and delivery charges unless otherwise noted.

 This list in non-exhaustive, i.e., it doesn't contain every single item that may be used in the project.

 This list is generic, i.e., it doesn't discriminate between the electronic requirements of all REACH projects as of 19th July, 2017.

## Command & Control

 |S No |Name                                                                                 |Cost  |Quantity|Notes                                                                                                                     |
 |:---:|:------------------------------------------------------------------------------------|:-----|:-------|:-------------------------------------------------------------------------------------------------------------------------|
 |1    |[Raspberry Pi 3 Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b)|$39.95|1       |Required; Used as a "master" computer for performing calculations and controls other electronics                          |
 |2    |[Arduino Uno Rev3](https://store.arduino.cc/usa/arduino-uno-rev3)                    |$24.95|1 - 2   |Required; Used as a "slave" microcontroller for transmitting data to and from various components and to the ground station|

## Motion Sensing

 The onboard electronics include a 9-Axis Inertial Measurement Unit (IMU) for sensing various motion data.

 |S No |Name                                                                                     |Cost  |Quantity|Notes|
 |:---:|:----------------------------------------------------------------------------------------|:-----|:-------|:----|
 |1    |[9-DOF Absolute Orientation IMU Fusion Breakout](https://www.adafruit.com/product/2472)  |      |1       |-    |
 |2    |[Arduino 9 Axis Motion Shield](https://store.arduino.cc/usa/arduino-9-axis-motion-shield)|$26.29|1       |-    |

 ***Note:*** Either module can be used; Essentially, both devices are the same, except for physical dimensions and elcetronic interfacing.

## GPS Tracking

 The onboard electronics include a GPS Receiver for accurate position plotting (used as a back-up against the IMU).

 |S No |Name                                                                                                              |Cost   |Quantity|Notes                                                                                               |
 |:---:|:-----------------------------------------------------------------------------------------------------------------|:------|:-------|:---------------------------------------------------------------------------------------------------|
 |1    |[SparkFun Venus GPS Logger](https://www.sparkfun.com/products/10920)                                              |$59.95 |1       |Capable of data-logging                                                                             |
 |2    |[NavSpark-GL](http://navspark.mybigcommerce.com/navspark-gl-arduino-compatible-development-board-with-gps-glonass)|$59.95 |1       |Essentially a developement board with a GPS receiver                                                |
 |3    |[Dexter Industries Arduino GPS Shield](https://www.amazon.com/gp/product/B006LR97BO/)                             |Unknown|1       |Accurate; Can't log data out-of-the-box (On-chip software has to be modified)                       |
 |4    |[Adafruit Ultimate GPS Logger Shield](https://www.adafruit.com/product/1272)                                      |$44.95 |1       |Capable of data-logging; Available on Amazon for 7,339 INR (Inclusive of taxes and delivery charges)|
 |5    |[USGlobalSat EM-506 (48 Channel)](https://www.sparkfun.com/products/12751)                                        |$39.95 |1       |Accurate; Can't log data out-of-the-box (Unknown if on-chip software can be modified to enable this)|

 ***Note:*** Any module can be used; Preference is given to data-logging capable modules

## Camera

 The onboard electronics include a camera for taking "breath-taking" pictures.

 |S No |Name                                                                                  |Cost     |Quantity|Notes                                                                                                            |
 |:---:|:-------------------------------------------------------------------------------------|:------- |:-------|:----------------------------------------------------------------------------------------------------------------|
 |1    |[Raspberry Pi Camera Module v2](https://www.raspberrypi.org/products/camera-module-v2)|1500+ INR|1       |8MP Camera; Various reseller list different prices; There is a No IR variant also Available for night photography|

## Communications Systems

The on-board electronics include a wireless communications system to transfer real-time telemetry data to the ground station.

 |S No |Name                                                                                                      |Cost   |Quantity|Notes                                                                                                                                                                                                           |
 |:---:|:---------------------------------------------------------------------------------------------------------|:----- |:-------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
 |1    |Satellite Communications Unit                                                                             |Unknown|1       |Tentatively supplied by the ISRO/DRDO due to high costs of such modules                                                                                                                                         |
 |2    |Proprietary RF/Microwave Communications Unit                                                              |Unknown|2       |Tentatively supplied by the ISRO/DRDO due to high costs of such modules; 1 Unit for the Rocket, 1 for the Ground Station                                                                                        |
 |3    |[XBee Sub 1GHz RF Communications Unit](https://www.digi.com/products/xbee-rf-solutions/sub-1-ghz-modules/)|Varies |2       |Cost varies for different modules; Certain long-range modules require additional hardware; Certain modules can be used with [Arduino Wireless SD Shield](https://store.arduino.cc/usa/arduino-wirelss-sd-shield)|

 ***Note:*** Any of the above mentioned modules may be used.

## Power

 |S No |Name                                       |Cost  |Quantity|Notes                                                                                |
 |:---:|:------------------------------------------|:-----|:-------|:------------------------------------------------------------------------------------|
 |1    |Vacuum Insensitive Rechargable Battery Pack|Unkown|1 - 2   |A module has yet to be identified; Quantity can vary depending on the battery's power|

## Other Parts

 |S No |Name                                       |Cost          |Quantity|Notes                                                                                                                                                                                                               |
 |:---:|:------------------------------------------|:-------------|:-------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
 |1    |Raspberry Pi to Arduino Bridge             |Unknown       |1       |Since the RAspberry Pi and the Arduino don't operate similarly, a bridge is require to connect them without damaging their circuits                                                                                 |
 |2    |Voltage & Logic Level Shifters             |$3.00 - $10.00|0 - 3   |Since most external modules work on 3.3V, but the Arduino works on 5V, a Voltage & Logic Level Shifter is required; A module is yet to be identified; Quantity can vary depending on number and type of modules used|
 |3    |Stacking Headers                           |Unknown       |0 - 3   |Used to connect multiple Arduino Shields (ICs containing modules for specific tasks) to the same Arduino                                                                                                            |

##
