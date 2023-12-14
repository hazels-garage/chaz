<a href="https://shop.hazel.cc/products/chaz-v03">
 <img src="https://img.shields.io/badge/-Purchase-%23000?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAABGdBTUEAALEQa0zv0AAAACBjSFJNAACHDwAAjA8AAP1SAACBQAAAfXkAAOmLAAA85QAAGcxzPIV3AAABCGlDQ1BJQ0MgUHJvZmlsZQAAKM9jYGBckZOcW8wkwMCQm1dSFOTupBARGaXAfoeBkUGSgZlBk8EyMbm4wDEgwIcBJ/h2DagaCC7rgsxiIA1wpqQWJwPpD0Acn1xQVAJ0E8gunvKSAhA7AsgWKQI6CsjOAbHTIewGEDsJwp4CVhMS5Axk8wDZDulI7CQkNtQuEGBNNkrORHZIcmlRGZQpBcSnGU8yJ7NO4sjm/iZgLxoobaL4UXOCkYT1JDfWwPLYt9kFVaydG2fVrMncX3v58EuD//9LUitKQJqdnQ0YQGGIHjYIsfxFDAwWXxkYmCcgxJJmMjBsb2VgkLiFEFNZwMDA38LAsO08APD9Tdt4gbWmAAAACXBIWXMAABJ0AAASdAHeZh94AAABC0lEQVQ4T2MAgv9kYqyCxGBMQUtFVwwxLBhVwEDG+n934PL/HQFLUMSxYEzBJp85/8td+/97aUf9jzcv+s/HIQgWZ2JkQlaH0MDOwgG2rcJtAhjXek773+G/+D8POz9QEzOyJhBGcMwVnf83es+GawThNr8FYDlGBka4OihGcEzlHcEaS1x6wJoq3Sf9L3PtQ1aMjBEcNTH9/xoShv9jzPL/13lOB2tKta76b6vihawBhhEcER7J/yxMrECF3v8TLEr+V7lP/t/qu+C/grAGsgYYRhUABUiD10ywJpCtDV6z/ksLKKKogWJUgXb/RcAAWQjEi/6HG2dhC00YxhTkZOXGEMOCsQoSwAz/AUZL+dIX/BrCAAAAAElFTkSuQmCC" /></a>
<a href="https://discord.gg/jP6hvgNN8r">
  <img src="https://img.shields.io/discord/989552667330228374?color=%237289da&label=%20&logo=discord&logoColor=%23fff&style=flat-square" />
</a>

# Chaz

![Chaz](images/chaz.jpg)
Low Profile, Choc Spaced QAZ-alike

## Features
* QAZ Layout
* Choc Spaced
* Integrated STM32F702 microcontroller

## Materials
* 1x [Chaz PCB](https://shop.hazel.cc/products/chaz-v03)
* 2x 2U Kailh Choc Stabalizers
* 37x Kailh Choc v1 Switches
* 37x Keycaps
  * 31x 1u 
  * 2x 1.25u
  * 1x 1.75u
  * 1x 1.5u
  * 1x 2u
  * 1x 2.25u
* 1x [Case](case/)
* 6x M2x6 countersunk screws  

## Build Steps
* Insert switches into switchplate
  * **NOTE**: There are 3 switches rotated differently from the rest.  Check the PCB to make sure you've got the correct orientation
* [Insert stabalizers](https://docs.keeb.io/choc-stabs)
* Place switchplate with switches onto PCB and press all the switches into their homes.
* Solder Switches
* Insert into case
* Screw Case to PCB from the bottom


## Firmware
To get into DFU, hold the DFU button on the bottom of the PCB while plugging in USB.

* [QMK](https://github.com/hazels-garage/qmk_firmware/tree/hazel/chaz)
* [VIAL](firmware/hazel_chaz_v03_vial.bin)
* ZMK Soon


## Changelog
* v0.3 - Current STM32F072CBT6 
* v0.2 - Unreleased and Unverified RP2040 
* v0.1 - Previously released ProMicro 
* v0.0 - Unreleased, but Verified ProMicro 