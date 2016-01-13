---
layout: post
title: Mindstorms EV3 vs VEX IQ
---

Let me give you the TL;DR right off the bat: 
if you plan on doing robotics, 
buy the [VEX IQ][iq]. 

The company, VEX Robotics, seems more focused than LEGO,
the starter kit is cheaper by a 100 USD *and* 
it has more structural parts than the EV3.

In the long run, you can move into their 
[VEX EDR][edr] line, which offers stronger
structural components (made of metal) and upgraded
electronic components. Of course, if you're *really serious*, 
I [recommend][roboticssets] looking at Arduino
and RaspberryPi -- you can build so much more than 
robots with them, but VEX is serious about their robots.

If you would like to know more details,
and why the EV3 was a better choice for me
(and might be for you too) read on.

## Comparison

[VEX IQ][iq] seems a direct competitor to the 
[LEGO Windstorms EV3][ev3] set. 
Both feature similar looking plastic pieces, with wheels, axles, etc.

Both feature some sort of "brain" for the robot, a programmable "brick",
sensors, motors, wheels, gears, and a plethora of structures to build
the frame of your robot. 

EV3 comes in two separate versions. The Home or Retail version is the 
version you can pick up in store at Toys'R'Us or on Amazon; 
the Education version, called Education Core, needs to be ordered
online from the LEGO education store, which by the way, seems to be 
a separate entity from the main LEGO entity. 

The two EV3 sets have somewhat different components, and the robots
that can be built *out of the box* differ too. The structural parts
are, I'd say, about 80-90% the same between the two.


| Parts                | EV3 Home (#31313)                          | EV3 Education (#45544)                     | VEX IQ                                 | 
|----------------------|--------------------------------------------|--------------------------------------------|----------------------------------------| 
| Structural           | 550+                                       | 540+                                       | 850+                                   | 
| Motors               | 2 lage, 1 medium                           | 2 lage, 1 medium                           | 4                                      | 
| Sensors - Touch/Bump | 1                                          | 2                                          | 2                                      | 
| Sensors - Distance   | 1, Infrared                                | 1, Ultrasonic                              | 1, Ultrasonic                          | 
| Sensors - Color      | 1                                          | 1                                          | 1                                      | 
| Sensors - Gyro       | 0                                          | 1                                          | 1                                      | 
| Brain                | ARM 9                                      | ARM 9                                      | [TI Tiva ARM Cortex-M4][tiva]          | 
| Brain - Ports        | 4 in, 4 out                                | 4 in, 4 out                                | 12, self-detecting                     | 
| Brain Interface      | USB, BT, MicroSD, (can attach WiFi dongle) | USB, BT, MicroSD, (can attach WiFi dongle) | USB                                    | 
| Controller           | IR Remote or iOS and Android apps          | IR Remote or iOS and Android apps          | Video-game like, available separately  | 
| Power                | Batteries, optional rechargeable           | 2050 mAh LiIon battery                     | Batteries, optional rechargeable       | 
| Software             | LEGO Mindstorms based on LabView           | LEGO Mindstorms / LabView                  | [Modkit for VEX][mk], a Scratch-like environment, or [RobotC for VEX][rcv], a C-like programming language | 
| Storage              | No                                         | Yes                                        | Yes                                    | 
| Price                | $349                                       | $349                                       | $249                                   | 


For the most part, it is obvious from the table above that VEX IQ is a better deal.

Further details:

- the EV3 has a much better brain - it's a modern ARM-based chip, much like the one in your cell phone. 
  More memory and processing power than the VEX IQ;
- brick connectivity also favors the EV3: you can connect via Bluetooth -- 
  making it possible to control the robot with your phone, 
  you can insert a MicroSD card (extremely useful when it comes to installing a better OS), 
  and you can even put it a WiFi dongle; 
  in contrast, the VEX IQ only supports USB (and wireless radio to talk to the remote);
- however, the VEX IQ not only has 50% more ports (12 vs 8 on EV3), 
  which means you can attach more motors or sensors,
  but they are self-detecting, whereas the EV3 has 4 dedicated to motors,
  and 4 dedicated to sensors (need only 1 sensor, but 5 motors? Tough luck,
  go buy a multiplexer);
- not sure if VEX IQ motors are servos. 
  VEX labels them as *smart* and there is control of the number of degrees it can rotate, 
  but if it was a servo you’d think they’d mention. Not sure if it truly matters,
  but it's worth pointing out because the EV3 motors are indeed servo motors;
- both kits have the same number of robots that can be built out of the box with the starter kit, 
  but in those robots there seem to be more variations on the EV3 side.
  I like that the EV3 instructions for a given robot also offer variations 
  in the sensors and secondary attachments; it makes it easier to build 
  a robot with slightly different abilities while keeping 98% of the frame
  already built;
- however, in looking over the instructions, I had an easier time following
  VEX IQ's than EV3's;
- Connecting parts seems easier with EV3
- Wider structural parts with IQ


[iq]: http://www.vexrobotics.com/vexiq
[edr]: http://www.vexrobotics.com/vexedr
[iqstarter]: http://www.vexrobotics.com/vexiq/products/kits-bundles/starter-kits/
[ev3]: http://www.lego.com/en-us/mindstorms/products/31313-mindstorms-ev3
[mk]: http://www.modkit.com/vex
[rc]: http://www.robotc.net/download/vexrobotics/
[tiva]: http://www.vexrobotics.com/brain-g.html
[roboticssets]: {% post_url 2016-01-05-choice-of-robotics-sets %}