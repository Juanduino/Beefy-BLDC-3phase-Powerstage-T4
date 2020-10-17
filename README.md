# Beefy-BLDC-3phase-Powerstage-T4

Powerful BLDC motor controller w. Field Oriented Control (FOC) which is the most silent and efficient way to drive a 3 phase brushless DC motor.

Using the TEENSY 4.0 modular MCU and the SimpleFOC library. (simplefoc.com & pjrc.com/store/teensy40.html)

The ultimate goal of the project is to make up to 4 BLDC nodes talk and synchronize on the CAN FD (Controller Area Network). 

By selecting the appropriate MOSFET voltage rating for the specifik battery voltage, you can achieve much lower Rds(on) specs. Within the family of Infineon PG-HSOF-8-1 (Package) MOSFETS, there are several different voltage ratings with varying Rds(on) ratings. 

Hardware:

Teensy 4.0 ( Teensy 4.0 features an ARM Cortex-M7 processor at 600 MHz, with a NXP iMXRT1062 chip, onboard LDO for 3.3v & USB plug)

Switching regulator LM5116 (Up to 100v w. external mosfets) for 12v rail used to switch powerstage. Since the regulator can handle a high amount of current, it can power external hardware such as turn lights, headlights, brake light and so on. 

In development.

![TOP](https://github.com/Juanduino/Beefy-BLDC-3phase-Powerstage-T4/blob/main/Images/TOP.PNG)

 



 

