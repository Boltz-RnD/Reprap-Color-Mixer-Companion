RCMC

RepRap Color Mixer Companion



"RCMC Gen 1" Is an External I2C Module, which is Developed to control the color output on a color Mixing hotend.

The hex code of the color output required is sent through i2c port and the RCMC automatically tunes the flow rate of the colors Cyan,Yellow,Margenta, White and black, to give the respective output.

RCMC has two Connectors which connects to the driver board

1.Stepper Driver connector shield
   
This shield Connector fits upon your printer board's(eg. RAMPS) extruder's stepper driver's connector and recieves the steps (signal) sent by the printer board.

2.I2C Connector

This Connector is used by RCMC to recieve the color command.

The CPU, based on the color Selected and Stepper driver's signal pulses calculates the resultant flow rates for diffrent Colors , and hence we get multicolor output.

We made this device as a companion to our 1st Gen Hotend and was closed source first, but since we also started by using reprap designs and the community's help, we decided to make RCMC open Source and give something back to the Community.

Feel free to contribute,remix,improve and adapt this work :) .
