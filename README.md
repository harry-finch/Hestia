# Hestia
A battery powered WiFi temperature sensor. 

Because of its rather simple function (showing the temperature), this board can also serve as a base for other IOT projects. It embeds many basic features:
- USB to UART (CH340G)
- battery management (MCP73831)
- battery level indicator
- load sharing between battery and USB
- ESP8266 minimal wiring

![](schematic.png)

![](3d.png)

## Temperature sensor
This project uses the MCP9808 chip to measure the temperature. The reason for choosing this IC is because it uses I2C and will provide a more accurate reading than the MCU's ADC.

## Display
The board features 4 holes to wire an OLED display. 
