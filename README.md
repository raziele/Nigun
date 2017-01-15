## Nigun (Melody)
RF down-converter for SDR

## PURPOSE
Allow low-frequency SDR (mainly RTL-SDR) to recieve wireless signals in frequencies higher than 1500MHz

## MAIN PROPERTIES
* Dynamic LO - LO will be determined by the user and programmed by the MCU
* Almost no filtering - will leave this challenge outside of this project scope
* Power up and programming via micro-usb connector. Should be able to power up from a USB power-pack (but probably not from a computer port)
* Highest RF frequency will be 3GHz
* Product also features a VCO for signal-generation purposes. VCO support should be 200-2700MHz

## DESIGN DETAILS
Can be found currently on http://slides.com/raziele/software-define-radio-4-5-6-7-8#/
All details should be updated here in the near future

## CURRENT STATUS
PCB design. Planning on ordering first prototype until the end of January 2017

## CREDITS
* All those who were patient enough to teach, review, and answer my endless questions
* Michele Perla and his HACK project - for the Atmel SAMD21E reference design

## LICENSE
I haven't dealt with the licensing part yet, though it will probably be under CERN OHL v. 1.2.
For now, please contact me for any licensing request.
