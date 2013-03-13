Arduino One Wire Search
=======================

Processing code for Ardunio to search for 1-wire devices and outputs address in hex to serial.

- Adapted by Gordon Turner from code by hacktronics:
  http://www.hacktronics.com/Tutorials/arduino-1-wire-address-finder.html

- 1-Wire temperature sensor attached to digital pin 3.

- Requires 1-wire Ardunio Library and Dallas Temperature Control Arduino Library.
- Included in Libraries folder or online:
    http://www.pjrc.com/teensy/arduino_libraries/OneWire.zip
    http://milesburton.com/Dallas_Temperature_Control_Library#Latest

- Sample serial output:
```
Searching for 1-wire devices.
Found 1-Wire device with address: 0x28, 0x85, 0x95, 0x3A, 0x04, 0x00, 0x00, 0xB7
No more devices found.
```