# WIPER CONTROL SYSTEM
## ABSTRACT
  Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. A windshield wiper is a very important part that permits a driver to collect the visual information at the time of precipitation of rain from the vehicle components aspect that influences the driver's safety and comfort. wiper consists of three operating speed. The wiper parts visible from outside the car are the rubber blade, the wiperarm holding the blade, a spring linkage, and parts of the wiper pivots. Driving a car in the rain is tough, so using wipers to clean the mirror. Here, I am using STM32 with arm based microcontroller to build the wiper control system.
## INTRODUCTION
Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. wiper consists of three operating speed.The wiper parts visible from outside the car are the rubber blade, the wiperarm holding the blade, a spring linkage, and parts of the wiper pivots.Driving a car in the rain is tough, so using wipers to clean the mirror.

## OBJECTIVES
  * To enable ACC mode, button is pressed one time.
  * To enable Ignition mode, button is pressed two times.
  * To turn on the wiper, button is pressed three times.
  * To turn off the wiper, button is pressed four times.

## SWOT ANALYSIS
### STRENGTH
  * It is used for safety purpose during driving.
  * It gives the clear visibility mode for drivers.
### WEAKNESS
  * It depends on drivers action not fully automatic.
  * Code errors leads to system faults.
### OPPORTUNITY
  * To add more functionalities.
### THREATS
  * If the wiper board repairs, it cannot replace quickly.
  * If the wiper stopped in the middle, we have to deal with it by mechanical section.

## 4 W'S and 1 H
### WHO
  *  Wipers are majorly used in automobile, railways and airline industries.
### WHAT
  *  Wipers are devices(Motor driven) with the flexible blade for wiping the wind shields.
### WHERE
  *  Wipers are used in cars, trains and aeroplanes.
### WHEN
  *  Wipers are used during the rains to clear the wind shields off of any water droplets to ensure clear visibility for the driver.
### HOW
  *  These motor driven arm devices with flexible blades can be used by the push of a button. When the button is pushed, the wiper starts to move and clear the windshield off of any dirt or water droplets.


## High Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | whether the button is pressed or not  | program execution |Engine starts | RED LED ON| SUCCESS |
| 2 | whether the button is pressed or not  | program execution | WIPER starts | GREEN LED ON| SUCCESS |
| 3 | whether the button is pressed or not  | - | Engine stops | LED TURNED OFF| SUCCESS |




## Low Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | whether the button is pressed again or not  | program execution | Engine starts | RED LED ON| SUCCESS |
| 2 | whether the button is pressed again or not | program execution | WIPER starts and speed of wiper is moderate | GREEN LED ON| SUCCESS |
| 3 | whether the button is pressed again or not | - | Engine stops | LED TURNED OFF| SUCCESS |



