# HTU21D_SoftI2C
This is an Arduino library for HTU21D, Si7021 and SHT21 Digital Humidity & Temperature Sensor.
The library was ported for Arduino/ ATtiny using SoftwareI2C, which allows any two pins to be SDA & SCL.

It was forked from https://github.com/enjoyneering/HTU21D and it depends on todbot's SoftI2CMaster library https://github.com/todbot/SoftI2CMaster

Supports all sensors features:

- read Humidity
- calculate Compensated Humidity
- read Temperature
- change Resolution
- soft Reset
- check Battery Status
- turn ON/OFF build-in Heater

# Instructions to use:
See HTU21D_Demo_SoftI2C.ino in 'examples' directory.
