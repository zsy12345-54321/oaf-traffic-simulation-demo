---
title: Real World Map Data
description: Generate Network through OpenStreetMap and Make It Closer to Real World
---

Generate Network through OpenStreetMap and Make It Closer to Real World

---

## SUMO Configuration File

You can find SUMO configuration file [here](https://github.com/zsy12345-54321/oaf-traffic-simulation-demo/tree/main/sumo/real-world)

### Simulation Overview

In this simulation, I simulated traffic in Mountain View. SUMO network is generated by using OSM Web Wizard based on real world map data (OpenStreetMap).
Once the network is generated, junctions and edges are cleaned up so that it is closer to real world.
And lastly, adjust the traffic light setting to compare the overall traffic performance of this simulation.


### Location

Area around Ingleside Terraces, San Francisco, CA 94112.

![map](https://i.postimg.cc/ZqVbCH0F/Screenshot-2022-10-28-181853.png)

### Simulation

[![SUMO -demo](https://res.cloudinary.com/marcomontalbano/image/upload/v1667018421/video_to_markdown/images/youtube--m02Ufum-r20-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/m02Ufum-r20 "SUMO -demo")

---

## Result

### Performance

 - **Duration**: 2.75s
 - **Real time factor**: 1410.42
 - **UPS**: 71864.166060


### Vehicles
 - **Inserted**: 1425
 - **Running**: 0
 - **Waiting**: 0

### Statistics
 - **RouteLength**: 1344.94
 - **Speed**: 9.92
 - **Duration**: 138.48
 - **WaitingTime**:11.68
 - **TimeLoss**: 38.76
 - **DepartDelay**: 0.59
