---
title: "License project: Digital servoing of a quartz oscillator"
date: 2022-03-11T18:35:26+01:00
draft: false

weight: 40





---

# Brief description of the project :


<p align = "justify"> A GPS need a stable source of time, a constellation of satellites equipped with atomic clocks transmitting a signal making it possible to trace the time of flight of the electromagnetic wave emitted by each satellite and, knowing their position, to trace back precisely to the frequency source transmitted by each satellite. A particularly suitable form for our purpose is the emission of a pulse every second (1 PPS – 1 pulse per second) with a front precise to within a few tens of nanoseconds. Many GPS receivers offer this feature. By measuring the number of oscillations of the quartz clocking the microcontroller between two pulses, we will be able to precisely measure the frequency of the quartz. The phase rotation condition to create an oscillator (multiple of 2π in the oscillation loop) is verified thanks to the capacitors placed on either side of the dipole formed by the quartz resonator. By adjusting one of these capacitors, we can shift the oscillation frequency of the circuit and thus slave its frequency on the 1 PPS in order to guarantee a period independent of the temperature or the environmental conditions of the microcontroller. Alternatively, this strategy makes it possible to produce excellent sensors thanks to the excellent references of atomic clocks, the stability of which is partly transposed to GPS receivers on the ground.
The quartz oscillator that we are going to use will be unstable, the goal of the projet is to put a corrector to make it stable. :</p>

The figure below represents the summary diagram of our project:

![projets](../projet1.png )








