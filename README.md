tl;dr: Download and install [NetLogo](https://ccl.northwestern.edu/netlogo/), download this code and open it with NetLogo, then click "setup" and then "go".

![GitHub Logo](screenshot.PNG)

# Agent-based model of wolf-sheep predation on a hex map.
This program combines NetLogo's built-in Wolf Sheep Predation model and NetLogo's Hex Cells code example to create a wolf-sheep predation model that generates population curves that are closer in shape to the curves produced by Lotka–Volterra "predator-prey" equations than does NetLogo's built-in Wolf Sheep Predation model. I built this model because I suspected that random agent motion on a hex map would be a more realistic model parameter than random motion on a tradtional grid. Though the raw data might seem to validate my hypothesis, my model also uses a different random-direction-selection procedure than the orignal. That or some other programming choice I haven't examined might also explain the difference in outputs.

The source models I started with come preinstalled with NetLogo:
* Models Library -> Code Examples -> Hex Cells Example
* Models Library -> Sample Models -> Wolf Sheep Predation (Docked Hybrid)

## todo
I wrote this on a deadline, so the code comments need review and the built-in "Info" tab documentation needs updating.