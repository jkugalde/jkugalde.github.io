---
layout: archive
title: "Paste extruder"
excerpt: "A Marlin-ified Replicator 2, with a syringe extruder adaptation for paste material"
collection: projects
author_profile: true
---

## Resume

The controller board for a Replicator2 exploded, so i replaced it with an Arduino Mega and Ramps, with the Marlin Firmware. Instead of using a filament extruder system i designed an hydraulic syringe extruder to print paste materials, which our Fablab was lacking. As the plunge of the syringe is pushed by a stepper motor, same as a common filament extruder, the new system was easily compatible with an usual 3D printer firmware such as Marlin, only some minor tweaks were done. Some files are at my [GrabCad site](https://grabcad.com/library/3d-printer-syringe-extruder-1).

<img src="/images/pastextruder.png" width="400">

Using different sizes of nozzle (2, 1 and 0.5 mm, printed with SLA), the machine was able to print using regular clay, fine clay, caramel and silicone in 2, 1 and 0.5 mm layer heights. The tests were performed using Repetier Host as the slicer software, varying it's parameters. 

<img src="/images/silicone.png" width="400">
<img src="/images/clay1.png" width="400">
<img src="/images/clay2.png" width="400">

