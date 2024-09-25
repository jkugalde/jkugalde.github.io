---
layout: archive
title: "N20 quadurped robot project"
excerpt: ""
collection: portfolio
author_profile: true
---

This project had several stages.

### Jumping robot

First, I wanted to make a cheap, small and "simple" legged robot. I had these N20 motors, which are pretty small, so the first step was to look for small sensors. I broke down some plastic servos to use their potentiometers. Then, I 3D printed [this](https://www.youtube.com/shorts/6vT5c4_hpZE) little guy.

### Modular servo actuator

As breaking down servo motors was not a good idea, I decided to use a small angle sensor (CJMCU-103). Instead of making a full body to integrate the motors, I decided to create a [module](https://github.com/jkugalde/N20-Servo-Module), which then I applied in another [jumping robot](https://github.com/jkugalde/Jumping-robot).

### Modular series elastic actuator I

I knew that for a smooth walking certain compliancy is needed, so I put a torsional spring at the output of the shaft in the module. Also, I included another angle sensor (so there is one in the input and another in the ouput, because if the spring is characterized, the torsion may be measured and provide a nice input for a more refined control. And so, the N20 series elastic actuator (SEA) was born. This first design was too weak (the printed spring broke easily), it was tested on a quadruped with 4 5-link legs, the (Pochitabot)[https://github.com/jkugalde/Pochitabot].

There are some pictures and videos [HERE](https://www.instagram.com/p/CnvOr4BjYhp/?igsh=cnA1MmIxdGFscnZx). The drivers were damaged after some testings.

### Modular series elastic actuator II

I made some changes in the module, particularly on the spring shape, and got a [better version](https://github.com/jkugalde/N20-SEA-module). I also changed the leg design of the robot, using the modules in series. This was the new [quadruped](https://github.com/jkugalde/Quadruped) robot. It uses a better h-bridge as a driver. 

The robot walked, but it was very inefficient. Some inputs were missing in the Arduino Mega to control all the modules, and the motors did not had enough torque to carry the weight. Probably because my N20s were not the originals from Pololu. 

### Modular series elastic actuator III

Finally, I repeated the process for a a [bigger motor](https://github.com/jkugalde/JGA25-370-SEA?tab=readme-ov-file))



---





