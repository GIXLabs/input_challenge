# Introduction

# Challenge
You are tasked with creating a hardware device to play [Tetris in the browser](https://tetris.com/play-tetris). We have provided some pre-programmed boards that handle most of the electronics and coding, but you will need to build the physical interface.

You must choose a target user and scenario for whom you're making your device.

# Table of Contents
- [Materials](#materials)
- [Electrical Assembly](#electrical-assembly)
- [Code](src/)

# Materials
![Supplies laid out](assets/components.svg)
- Raspberry Pi Pico main board
- Micro USB cable
- Switches
- Potentiometer
- Anything you can find in the Prototyping Labs

# Electrical Assembly
The button wires go into the green terminal blocks with two holes. It does not matter which end goes into which hole since these buttons are not polarized. You will need to depress the square on the top of the green terminal block to let the wire slip in.

![Gif of plugging wires in](assets/wiring.gif)

The potentiometer wires go into the green terminal blocks with three holes. The black wire needs to go into the center hole, but the other two can be place in either side hole (but not the same one!).

![Wired potentiometer](assets/wiring_potentiometer.svg)

# Operation

| Pin | Keystroke |
| --- | --- |
| GP2 | Left |
| GP3 | Right |
| GP4 | Rotate |
| GP5 | Down |

The potentiometer (knob) controls how fast bricks fall by "feathering" the down button. If the potentiometer is not wired, this feature will be deactivated.