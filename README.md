<!-- Please do not change this html logo with link -->
<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# AVR128DB48 Gain and Offset Calibration of the Analog Signal Conditioning (OPAMP) Peripheral

A new feature introduced in the AVR® DB MCU is the Analog Signal Conditioning (OPAMP) peripheral. The OPAMP peripheral can be configured as a PGA, in this example the internal DAC and ADC are used to calibrate gain and offset for the PGA. For more information on the calibration procedure, see the application note.   

## Related Documentation

* ANxxxx - Gain and Offset Calibration of the Analog Signal Conditioning (OPAMP) Peripheral
* [AVR128DB48 device page](https://www.microchip.com/wwwproducts/en/AVR128DB48)

## Software Used
* [Atmel Studio](https://www.microchip.com/mplab/avr-support/atmel-studio-7) 7.0.2397 or later
* Atmel Studio AVR-Dx_DFP version 1.3.67 or later

## Hardware Used

* [AVR128DB48 Curiosity Nano](https://www.microchip.com/wwwproducts/en/AVR128DB48)

## Setup

* No external hardware setup needed

## Operation
* Connect the AVR128DB48 Curiosity Nano to a computer using a USB cable
* Download the zip file or clone the example to get the source code
* Open the .atsln file with Atmel Studio
* Press *Start Without Debugging* (CTRL+ALT+F5) to run the application

## Conclusion
After going through this example you should be able to calibrate the gain and offset of the OPAMP configured as a PGA.
