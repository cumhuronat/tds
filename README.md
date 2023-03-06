# ESPHome TDS Sensor 
This is a tds sensor based on esp32-pico-d4 to be used for analyzing the status of a water purifier filters.
## Features

 - Powered by esphome
 - AC current generator to prevent polorization
 - OLED screen
 - Production ready
 - ADS1115 for precise voltage readings.
 - Temperature sensor for accurate tds calculation
 - 2.4GHZ PCB Antenna

## Pictures

![pcb](https://github.com/cumhuronat/tds/blob/master/images/pcb.jpg?raw=true)

![case](https://github.com/cumhuronat/tds/blob/master/images/case.jpg?raw=true)

![probe](https://github.com/cumhuronat/tds/blob/master/images/probe.jpg?raw=true)

![final](https://github.com/cumhuronat/tds/blob/master/images/final.jpg?raw=true)

## Notes

The pcb doesn't include a usb-ttl module hence you will need an external programmer like USB - TTL UART CP2102 or similar. H2 Header has the necessary pins for this purpose (3V3 GND RX TX).

You will need to order a probe with NTC 10k + electrodes. I've used:
https://www.aliexpress.com/item/1005004315383393.html

Part of the schmatic design is based on:
https://wiki.dfrobot.com/Gravity__Analog_TDS_Sensor___Meter_For_Arduino_SKU__SEN0244

The pcb includes headers for an 128x32 oled screen. I've used the following screen but you can use any oled screen with the same pinout.
https://www.aliexpress.com/item/1005004900370420.html