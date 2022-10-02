---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

These are my main projects, in which i work from time to time. I have made some other stuff, but less fancy and more hardware focused, they are probably on my GrabCad page or in "Other projects" at the bottom of this page.

## N20 Servo module

I made a 3d printed housing for a N20 type dc motor and joint it with an angle sensor (CJMCU-103). It controls shaft position using a PID control. [Link](https://github.com/jkugalde/N20-Servo-Module) to the github repository.

<img src="/images/module.png" width="300">

## Jumping robot

Using 2 N20 Servo modules i made a jumping robot. [Link](https://github.com/jkugalde/Jumping-robot) to the github repository.

<img src="/images/Legs.png" width="300">

## Quadruped

Using three N20 Servo modules per leg, i pretend to make a tetrapod using an attiny.

<img src="/images/quad.png" width="300">

## SCARA 3DP

Using some spare parts and the remains of my ANETA8 i made a small SCARA robot arm with an electromagnet as effector. [Link](https://github.com/jkugalde/SCARA-3DP) to the github repository.

<img src="/images/scara.png" width="300">

## Soft robot worm

My thesis project, a worm-like soft robot with artificial skin. The worm developed a crawling gait inside cavities and had soft sensors acting as pressure and deformation sensors to control the algorithm.

<img src="/images/softwo.png" width="300">

--------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------

# Other projects

## T-Slot Workbench

[Link](https://jkugalde.github.io/portfolio/tslottable/)

<img src="/images/iso1.png" width="300">

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
