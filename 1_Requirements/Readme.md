# WIPER CONTROL SYSTEM
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

## 4 W's and 1 H







## High Level Requirements
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | whether the button is pressed or not  | program execution | Engine starts | Red Led ON| SUCCESS |
| 2 | whether the button is pressed or not  | program execution | wiper starts | Blue Led ON| SUCCESS |
| 3 | whether the button is pressed or not  | program execution | wiper starts | Green Led ON| SUCCESS |
| 4 | whether the button is pressed or not  | program execution | wiper starts | Orange Led ON| SUCCESS |
| 5 | whether the button is pressed or not  | - | Engine stops | Led Turned OFF| SUCCESS |









## Low Level Requirements
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | whether the button is pressed again or not  | program execution | Engine starts | Red Led ON| SUCCESS |
| 2 | whether the button is pressed again or not | program execution | wiper starts and speed of wiper is slow | Blue Led ON| SUCCESS |
| 3 | whether the button is pressed again or not | program execution | wiper starts and speed of wiper is moderate | Green Led ON| SUCCESS |
| 4 | whether the button is pressed again or not | program execution | wiper starts and speed of wiper is good | Orange Led ON| SUCCESS |
| 5 | whether the button is pressed again or not | - | Engine stops | Led Turned OFF| SUCCESS |
