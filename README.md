# PinephonePogoBreakout

A breakout board for the Pinephone's expansion port, which consists of 6 pogo pins connected to I2C (SDA and SCL), the battery (at 3.8V), a 3.3V power rail (or is it 5V? Not confirmed yet), an interrupt pin, and GND.


I will go back and update the silkscreen layer to indicate which I2C pin is which, once I find out myself.

Also the standoff/washer .stl file is for 3d printing; it's used because I left the three holes in the pcb larger than necessary to allow some wiggle room, and the machine screw (which is M1.4 by the way) will slip through it otherwise.



![alt text](https://github.com/SMR404/PinephonePogoBreakout/blob/master/comparisonPic.jpg "Comparison with and without breakout board attached")

![alt text](https://github.com/SMR404/PinephonePogoBreakout/blob/master/boardScreencap.PNG "KiCad screenshot")
