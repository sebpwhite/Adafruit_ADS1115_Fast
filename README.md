Adafruit_ADS1115_Fast
================

Based on Adafruit's Library for ADS1x15 series of 12-bit and 16-bit Analog to Digital converter breakout boards.

Changes:
Focus on ADS1115 (1015 support more than likely broken)
Update sample rates to match ADS1115
Reduced sample delay (and increase sample rate) in single shot mode.

Working On:
Implementing continuous sampling mode with RDY pin. Intention is to be able to use interupts to read a sample when the ADC is finished with a conversion so we can get closer to utilising the full sampling rate of the chip.

<!-- START COMPATIBILITY TABLE -->

## Compatibility

Board               | Tested Works | Doesn't Work | Not Tested  | Notes
----------------- | :----------: | :----------: | :---------: | -----
Particle Photon  |       X      |             |             | Use SDA/SCL on pins D1 and D0, ALERT on D2 for samples.

 
  * Particle Photon : Particle Photon 3.3V (https://docs.particle.io/datasheets/kits/photon)

<!-- END COMPATIBILITY TABLE -->
