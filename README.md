
# Respository-of-WBR-SH
This respository collects the resources of WBR-SH 


## Competitors 
[Liftup](https://www.kickstarter.com/projects/getliftup/liftup-a-modern-resistance-band-that-tracks-your-w/description)
is a sensorised resistance band, with loadcell sensor only, on kickstarter. Cancelled in April 2016

## Hardware Design

**Tools for design:**

[Circuitmaker](https://circuitmaker.com/): A community version of Altium Designer

[AppCAD](http://www.hp.woodshot.com/): RF circuit calculator

Similar project: [Nordic Thingy:52](https://www.nordicsemi.com/eng/Products/Nordic-Thingy-52)


### MCU 
nRF52832

[Nordic General info center](https://infocenter.nordicsemi.com/index.jsp)

#### RF reference
This blog generally introduces the hardware and RF design of nRF52 chips
[General PCB design guidelines for nRF52](https://devzone.nordicsemi.com/blogs/870/general-pcb-design-guidelines-for-nrf52/)

Antenna tuning whitepaper by Nordic 
[Antenna tuning](http://infocenter.nordicsemi.com/pdf/nwp_017.pdf)

##### Antenna datasheets

This one is used in nRF Thingy project (52832):
[2450AT18B100](https://www.johansontechnology.com/datasheets/antennas/2450AT18B100.pdf)

This one is used with nRF51822:
[2450AT43A100](https://www.johansontechnology.com/datasheets/antennas/2450AT43A100.pdf)

[Johanson Chip Antenna selection guide](https://www.johansontechnology.com/downloads/chip-antenna-selection-guide.pdf)

### Sensors
#### IMU sensor: MPU-9250
9-Axis sensor

[Product page MPU-9250](https://www.invensense.com/products/motion-tracking/9-axis/mpu-9250/)

Reference design of using the MPU9250 on nRF5288: nRF Thingy.
[FW of nRF Thingy](https://github.com/NordicSemiconductor/Nordic-Thingy52-FW)

#### Atmospheric pressure sensor: LPS25H
24-bit 25 Hz ODR

[Product page LPS25H](http://www.st.com/en/mems-and-sensors/lps25h.html)

Reference design of using the MPU9250 on nRF5288: nRF Thingy.
[FW of nRF Thingy](https://github.com/NordicSemiconductor/Nordic-Thingy52-FW)

### Manufacturer

#### PCB Pool
[Specifications](http://www.pcb-specification.com/uk)
