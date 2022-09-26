---
title: "Paste extruder"
excerpt: "A Marlin-ified Replicator 2, with a syringe extruder adaptation for paste material"
collection: projects
---

## Resume

The controller board for a Replicator2 exploded, so i replaced it with an Arduino Mega and Ramps, with the Marlin Firmware. Instead of using a filament extruder system i designed an hydraulic syringe extruder to print paste materials, which our Fablab was lacking. As the plunge of the syringe is pushed by a stepper motor, same as a common filament extruder, the new system was easily compatible with an usual 3D printer firmware such as Marlin, only some minor tweaks were done. Some files are at my GrabCad site, but i will update them and organize the repository at my Guthub.

Using different sizes of nozzle (2, 1 and 0.5 mm, printed with SLA), the machine was able to print using regular clay, fine clay, caramel and silicone in 2, 1 and 0.5 mm layer heights. The tests were performed using Repetier Host as the slicer software, varying it's parameters. 


![silicone](/images/silicone.png "Silicone cube")
![clay1](/images/clay1.png "clay")
![clay2](/images/clay2.png "more clay")
