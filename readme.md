# Erica HAT
A raspberry pi HAT containing the interfaces used on Erica.
This board has the hardware for all of Erica's functions, however only some will be populated on each pi

## Board modules

* **ID EEPROM** as per the hat specification.
* **Button and Status Indicator** to provide information on the state of the pi.
* **DC Input** allows powering of the pi through the HAT.
* **GPIO Breakout** an 8P8C connector containing broken out GPIO, used for the touch sensors.
* **Temperature Sensor** for measuring Erica's internal temperature.
* **Real Time Clock** maintains a time reference when Erica is powered off.
* **Webcam Led Controller** controls the brightness on the eye webcam LEDs also has USB passthough to the webcam.
* **Servo Connector** for connecting the eye servos (directly connected to gpio for use with servoblaster).
* **DMX Interface** for controlling DMX fixtures from the pi.
* **Debug USB-serial** connects to the pi's console for debugging.




