# TPA3251 Audio Amplifier (Current main rev v0.1a)

Repository has an amplifier board under development for self entertainment and for self studies.

### Initial targets:
With this project I want to achieve the following:

1. The output THD + N should remain low: **<0.1%**. 

    * The solution of capturing this measurement requires personal research. The metric is specified.
2. Make the amplifier sound good!
3. Learn the design process and learn the tools over the project advancement.
4. Learn how to design filters.

---
### Hardware requirements:

* Amplifier circuit (Done)
* Pre-amplifier circuit
* UI (indicator LEDs, volume control)
* 2x speaker output ports
* 1x USB-C Input interface --> DAC module integration (might develop my own one, if interested)
* 1x 3.5mm Input
* 1x Power Flip Switch (I always wanted such)
---
#### Defined Characteristics:
V = 24V - 36V (most cases) 

#### Power tree: 
36V TPA3251_PVDD
  --> 15V 
    --> 12V TPA3251_VDD
      --> 3.3V LEDs, (MCU?)
      
(might require 5V)

---
### Known issues:
1. Buck converter wrong connection
2. Indicator LED driver MOSFETs have a wrong arrangement
---
# Future development as of 5th of March, 2026

Consider using 4-layer board --> miniturize
Start designing pre-amplifier and volume control
