

## Hardware Version 2 Installation
The setup guide for Arduino Zero can be found here:
https://learn.sparkfun.com/tutorials/samd21-minidev-breakout-hookup-guide/setting-up-arduino

The DW1000 Arduino library can be found here:
https://github.com/thotro/arduino-dw1000

The modified DW1000 library is DW1000-20191218T032326Z-001.zip, the file Footstep.h has network setting that needs to be re-configured for the system, including

- NETWORK_ID
- ANCHOR_NUM
- TAG_NUM
- ANCHOR_ID_OFFSET
- TAG_ID_OFFSET 
- RADIO_RESET_COUNT

Decawave 1000: 
http://www.marketwired.com/press-release/decawave-launches-dwm1000-module-for-precise-indoor-location-and-communication-1925616.htm