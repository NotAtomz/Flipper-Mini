# Flipper Mini Beta
This is a firmware for a device called LilyGo Display with a ESP32S3.
The firmware is designed to be Similar to the flipper zero.
The firmware was designed to use:
* Bad USB
* WiFi
* Bluetooth
* Infrared
* GPIO pins
----------------------------------------------------------------------
The open source project will be released on the full release as this is
currently development builds to test things such as ble spamming, wifi
beacon flooding, tv and other infrared devices controlling, and more.
----------------------------------------------------------------------
This was the last recovery file i could find after erasing the project
completely 
make sure you upload this through the ESP Tool
upload the bootloader bin as 0x0000
upload the partions bin as 0x8000
upload the firmware bin as 0x10000
and boom
connect the ir led to pin 43 to use it btw
