# Input shaper PCB

## Backstory

Hi, thank you for taking interest in my design!
In the summer of 2021 I saw the crampon PCB made by annex engineering. It looked like a pretty simple design and I have always been interested in PCB design so I thought this would be a fun beginner project. The result of my adventure can be found on this GitHub page. However, Annex's design probably looks, feels and works better. I have not been able tot test my design yet as well. So proceed with caution!

The link to Annex's product can be found here: [Annex engineering home page](https://annex-engineering.eu/)
Link to their Crampon GitHub page: [Crampon GitHub page](URL "https://github.com/Annex-Engineering/Annex_Engineering_PCBs/tree/master/crampon")

## Technical details

This PCB is based on the RP2040 chip. the PCB uses an ADXL345 accelerometer to measure the harmonic frequencies of your 3d-printer during a input shape tuning test.
More information about input shaping can be found here: [Klipper3d.org](URL "https://www.klipper3d.org/Resonance_Compensation.html")
I have also added a BME280 temperature, barometric pressure and humidity sensor, but this is not mandatory.

This is one of my very fist PCB designs and I made it by implementing schematics I found on the internet.
My sources are listed here:

overall design: [RP2040 Hardware design](URL "https://datasheets.raspberrypi.com/rp2040/hardware-design-with-rp2040.pdf")
BME280 design:  [BME280 datasheet](URL "https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme280-ds002.pdf")
ADXL345 design: [ADXK345 datasheet](URL "https://cdn.sparkfun.com/datasheets/Sensors/Accelerometers/ADXL345_Breakout.pdf")

## Manual

to be added.
