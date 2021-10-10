# ESP-HEX
Tileable hexagonal PCB for ESP8266 modules. If you like the design consider buying me a coffee:

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/Hexopholes)

Design goal was to support a large number of ESP8266 modules for as little money as possible. 
Each board supports six ESP8266 modules powered by a common LM2596 DC-DC module. Capacitors can be added for each ESP board.

_PLEASE NOTE_: While all layouts are sized to accept as wide a range of sizes as possible, we're working with the cheapest Chinese-made electronics. 
There is always a risk your parts won't fit the board. The DC-DC connections are larger than needed, and there are pads on the boards for flying leads if the pins don't line up.

_WARNING_: These boards tile, but THEY MUST NOT BE ROTATED! If you do you will connect power to ground and have a very bad day.

Build sequesnce:

*Install DC-DC module.

*Connect power supply.

*Set the OUT of the DC-DC module to 3.3V (Do this now or you'll kill the ESPs).

*Disconnect power.

*Solder 2x4 pin ESP8266 connectors.

*Power the board and test.

*Repeat and tile boards together.



![Alt text](working_image.png?raw=true "Boards working")