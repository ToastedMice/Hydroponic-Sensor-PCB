# Hydroponic-Sensor-PCB

A custom PCB designed for managing a smart hydroponic system. It will definitly need some modification as my use case is so specifc. It integrates components needed to automate water and nutrient delivery using peristaltic pumps and sensor feedback. I chose to use cheap sensors rather than good ones so that might need changing too.

## Features

- **5x N-Channel MOSFETs**  
  For switching 0-36v peristaltic pumps, I used NRF20L01's but it would probably be better for Rpi to get some logic level mosfets.

- **Sensor Support**  
  Has a port for pH sensor,EC, i2C USB port for a TSL2591 light sensor.

- **Microcontroller-Friendly**  
  Headers make it easy to connect additional i2c or 5v devices.

- **Compact Form Factor**  
  Layout for enclosure mounting and wire management. pH, EC, Battery could go inside a case
