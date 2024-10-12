# remote_esphome
I used a SparkFun WiFi IR Blaster (ESP8266)  WRL-15031 [https://www.sparkfun.com/products/1503](https://www.sparkfun.com/products/15031) , put it into a hammond box so it would work with ESPHome and Home Asssistant. This lets me control a SMSL AD18, a TEAC AI-101DA and a Toshiba TV. I did create a companion automation on the Home assistant side to automatically swap the output from speaker to headphones. 

I'd reccomend to pick an oversized box, that way you could fit a FTDI board in it as well to allow easy usb firmware upload and not relying on OTA. The ESP doesn't have the greatest memory size and I removed spaces between objects so the firmware can fit for an OTA update, but this is enough for my use-case. 
