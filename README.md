# Regulated_Power_Supply
A regulated power supply built from scratch, regulates and delivers a DC voltage of 0-20v or -18-0v.
The power delivered is noisy and unstable, the components are also fragile so it shouldn't be used over it's expected nominal current of 1A. This is built for test purposes only. 

The power supply consistes of three phases, a transformer which turns 120Vrms AC to 24vrms AC, a rectifier bridge and filtering capacitors with a maximum current of 1A. Finally, the regulation stage, where the lms, capacitors and diodes ensures a regulated voltage value within the mentioned thresholds. 

This repository contains the images of the full power supply, as well as the files to run the simulations of it using proteus 8 or above. 
