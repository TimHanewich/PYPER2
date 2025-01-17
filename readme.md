# PYPER 2: Python-Based 3D-Printed Electric Rover
![PYPER 2](https://i.imgur.com/wpYqAAz.jpeg)

A fully 3D-printed electric rover that uses common inexpensive components, is powered by a Raspberry Pi Pico, and programmed in MicroPython. PYPER 2 borrows design elements and carries over some components from [PYPER](https://github.com/TimHanewich/PYPER), my original design.

## 3D-Printing the Parts
![blender](https://i.imgur.com/SdJzHiA.png)

PYPER 2 was designed in [Blender](https://www.blender.org/). You can find PYPER 2's Blender design file in this repo as [design.blend](./design.blend).

## Electronic Wiring
![wiring](https://i.imgur.com/IS3WrjF.png)

PYPER 2's wiring diagram was developed in [draw.io](https://draw.io). You can open [wiring.drawio](./wiring.drawio) on **draw.io**.

## The Code
PYPER 2 is programmed in MicroPython and is designed to run on a Raspberry Pi Pico. You can find the entire source code in the [src folder](./src/). Update the settings in the [settings.py](./src/settings.py) module according to your specific wiring, deploy to a Raspberry Pi Pico using Thonny, and you should be good to go!

## Current Design Issues
PYPER 2 is not perfect. I plan to update a few things in the future that are, as of now, not ideal:
- **Make the Raspberry Pi Pico's USB port easily accessible**: Very difficult to get to Raspberry Pi Pico USB port without taking lid off and rear right spacer. 
- **Tie rod redesign**: The tie rod (component that holds the front two steering uprights together) is not an elegant design.
- Perhaps improve wire organization, if possible.

## Miscellaneous Design Notes
- Specs of original drive shaft gear: https://i.imgur.com/a3ub9se.png
- Specs of original motor gear (attached to TT motor): https://i.imgur.com/Kuyyccg.png