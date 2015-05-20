FT-330-Arduino-Example
======================

This is a simple Arduino example for the FT-330 Series Turbine Flow Sensor. These sensors are sold by KegBot

These sensors just pulse the white wire as fluid is flowing through it. Basically, 10,000 puleses per gallon.

Beware the flow direction: (arrow on the bottom of the sensor)

Beware the serial Baud Rate: 9600 baud

Beware the pinout:

```
red   = 5-24 Volts
|
>
> 10k Ohm resistor between red and white
>
|
white = Pulses out (to pin 7 on the Arduino)
black = ground/0 volts

```

Beware the data sheet:

```
http://www.gemssensors.com/~/media/GemsNA/NEW%20CATALOG%20FILES%20-%202013/FT-330.pdf
```
