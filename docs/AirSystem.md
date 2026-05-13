---
title: AirSystem
layout: default
nav_order: 4
---

## AirSystem
I've created two types of air system to support students in their pneumatics prototyping. Contact me if you want to borrow these (Katrien van Riet in TU/e Teams).

### AirSystem original (Waveshare RP2040 PiZero based)
This system lets you quickly swap out 4 'air units', each consisting of 1 pump, 1 solenoid valve, and 1 pressure sensor. This is nice for testing shape-changing interfaces, for example, where different areas need to show different inflation/deflation behaviours.

The AirSystem is accompanied by a detailed user manual and Arduino library with example sketches to get you started quickly. Find the documentation here: [link](https://github.com/kvriet/AirSystem-for-Soft-Robotics).

![AirSystem with 4 units connected](https://raw.githubusercontent.com/kvriet/AirSystem-for-Soft-Robotics/main/Media/modular%20Air%20System.jpg)


### Airsystem compact (Waveshare ESP32 C3 Zero based)
This system is more integrated, consisting of 2 pumps, 2 solenoid valves, and 2 pressure sensors. This is nice when you want a control box that is not too big, although it's probably still too big to fit inside a smaller prototype. However, you can always have the AirSystem to the side and run silicone tubes to your prototype for actuation. You can swap out the pumps and solenoid valves for other 12V components, if desired, so you have some more freedom in which components you want to use.

The AirSystem is accompanied by a detailed user manual and Arduino library with example sketches to get you started quickly. Find the documentation here: [link](https://github.com/kvriet/AirSystem-ESP32-for-Soft-Robotics)

![AirSystem compact](https://raw.githubusercontent.com/kvriet/AirSystem-ESP32-for-Soft-Robotics/main/Media/airsystem_ESP32.png)
