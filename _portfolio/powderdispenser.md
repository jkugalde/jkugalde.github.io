---
layout: archive
title: "Powder dispenser"
excerpt: "A 3d printed powder dispenser, uses a 12V DC Motor."
collection: portfolio
author_profile: true
---

# Summary

A 3d printed powder dispenser, works with an Auger screw inside a barrel, powered by a geared DC Motor. It is quite simple.

<img src="/images/powder.png" width="300">

[Here](https://grabcad.com/library/powder-dispenser-4) are the CAD files.
[Here](https://github.com/jkugalde/Powder-Dispenser) is the github repository.

# Design

An auger screw does all the magic, pushing the powder that falls at the inlet of the container from the hopper. The screw is attached to the shaft of a tube and this to a geared motor with a set screw, the other end of the auger rotates inside a funnel.

The containter of the powder is made from an acrylic tube which fits on the hopper and is closed on the top by the motor support that also acts as hopper.

# Tests

## Electronics

There are a lot of options to control a DC Motor, a good one is with an H Bridge, like the L298N. You will also need an Arduino, some cables and a 12V/2A power source. Also a load cell if you want a closed loop control.

<img src="/images/elec2.png" width="700">

## Software

I wrote a simple program in Arduino, which controls the direction and speed of the dispenser if you want to try it that way. Remember that it only dispenses in one direction, the other one would be something like a retraction. 

## Setup

The dispenser is part of a bigger machine, you can read more about it [here](https://gitlab.com/fablab-u-de-chile/biomixer). There are more dispensers in the machine, to deliver different type of powder materials. These powders fall in a vase, where the quantity is roughly controlled with a load cell.

## Tests

Works real fine #trustme. We tested it with agar-agar and calcium propionate and it is very consistent. It does not work with powders that are too fine, like chalk, it agglomerates on the intlet an does not fall.
