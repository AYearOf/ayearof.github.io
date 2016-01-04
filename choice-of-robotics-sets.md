# Choice of Robotics Sets

The first choice I had to make in pursuing my [Year or Hobbies: Robotics] was which direction to go in? The choices are threefold: already built robots — leaning more towards programming (eg OWI) robotics kits (Mindstorms, Vex), or the free-form route of Arduino (or RaspberryPi). 

Here are my constraints:
- Multi-function: if they only did one thing, it would be pretty boring no matter how well they do that one thing;
- Programmable: I want my labyrinth solver to figure out the path by itself;
- Not overly complex: it's a hobby, so satisfaction should be achievable without heroic efforts; additionally, I'd like to be able to bring my 12-year old step-daughter into these adventures;
- Should allow for learning something new, yet be focused at the same time: I don't want to have to juggle 3+ disciplines at the same time (and programming is already a must-have)

## Already Built Robots
Great choice if the intent is to lean more towards the programming side. Here's a great example: 
![Ozobot Bit]
[Ozobot Bit](http://ozobot.com/products/ozobot-bit) looks like a blast if you want to built a follow-the-line bot.

[OWI's Robots](http://www.owirobot.com) are also great resources at great prices: from the robotic arm — probably the closest you'll come to true industrial robots — to the solar kits, they're all excellent. 

On the downside, their fixed shape constrains how much you can do with them. It might be difficult to build a roaming robot out of the fixed robotic arm. But maybe that's just my imagination lacking.

## Robotics Kits

The beginner robotics systems have long been dominated by [LEGO Mindstorms](#ev3). In this world, [VEX Robotics](#vex) is a new entrant, but they did do a great job building a environment to rival LEGO’s. They have not one, but three levels of sets: [VEX IQ](#vexiq), [VEX EDR](#vexedr), and [VEX PRO](#vexpro).

### VEX IQ
[VEX IQ](#vexiq) seems a direct competitor to the [LEGO Windstorms EV3](#ev3) set. Both feature similar looking plastic pieces, with wheels, axles, e.t.c.

|  Parts | EV3 (#31313) | EV3 (Education #45544) | IQ |
|--------|--------------|------------------------|---|
| Structural |     550+ |                 - |  850+ |
| Motors | 2 lage, 1 medium | *(same)* | 4 |
| Sensors  - Touch/Bump | 1 | 2 | 2 |
| Sensors  - Distance (Ultrasonic) | 0 | 1 | 1 |
| Sensors - Distance (Infrared) | 1 | 0 | 0 |
| Sensors  - Color | 1 | 1 | 1 |
| Sensors  - Gyro | 0 | 1 | 1 |
| Brain | ARM 9 | ARM 9 | [TI Tiva ARM Cortex-M4](http://www.vexrobotics.com/brain-g.html) | 
| Brain - Ports | 4 in, 4 out |  *(same)* | 12, self-detecting |
| Brain Interface | USB, Bluetooth, MicroSD, (can attach WiFi dongle) |  *(same)* | USB |
| Controller | IR Remote or iOS and Android apps |  *(same)* | Video-game like, available separately |
| Power | Batteries, optional rechargeable | 2050 mAh LiIon battery | Batteries, optional rechargeable |
| Software | LEGO Mindstorms based on LabView | *(same)* | [Modkit for VEX](http://www.modkit.com/vex), a Scratch-like environment, or [RobotC for VEX](http://www.robotc.net/download/vexrobotics/), a C-like programming language |
| Storage | 
| Price | $349 | $349 |  $249 |

- Not sure if VEX is a servo. VEX labels them as smart and there is control of the number of degrees it can rotate, but if it was a servo you’d think they’d mention. Not sure if it truly matters.

## DIY - All of It

At the opposite end of the already built robots stands the world of Arduino and, to a larger extent, RaspberryPi (it seems [Arduino is a better choice for task-oriented systems, while RaspberryPi for longer-running systems](#arduino-vs-rpi)).

And that's a *beautiful* thing. You start from the core components and add only what you need: servos, sensors, etc. You buy only what you need, thus not only keeping the costs to a minimum, but you have the ability to select the best suited components; of which there are plenty.

The support is spectacular, both on the hardware and on the software side.

The amount of fabrication tends to be larger than in the Mindstorms case. You need to hand built all the frames you need for your robots; something like the [Track3r](#track3r) might not take a lot, while I wouldn't even know where to start for the [R3ptar](#r3ptar). On the flip side, you can build considerably larger kits than you can with LEGO. 

You will also have to learn, if you don't know already know, a good deal about electronics and electric circuitry. While I do have a BS in Computer Science & Electrical Engineering, I remember none of it, and to be honest it seemed a bit more than I wanted to *start* with.

That doesn't mean Arduino will not part of my world - I can already see it showing up in a support scenario: I want to build a better [line following robot](#line-robot), one that [also obeys traffic lights](#line-robot-traffic); those traffic lights will likely be built using an Arduino kit.

## Mindstorms: Retail vs Education


[arduino-vs-rpi]: http://makezine.com/2013/04/15/arduino-uno-vs-beaglebone-vs-raspberry-pi/
[track3r]: http://www.lego.com/en-us/mindstorms/build-a-robot/track3r
[r3ptar]: http://www.lego.com/en-us/mindstorms/build-a-robot/r3ptar
[line-robot]: 
[line-robot-traffic]:
[ev3]: http://shop.lego.com/en-US/LEGO-MINDSTORMS-EV3-31313?p=31313&track=checkprice
[vexiq]: http://www.vexrobotics.com/
[vexiq]: http://www.vexrobotics.com/vexiq?ref=hometile
[vexedr]: http://www.vexrobotics.com/vexedr?ref=hometile
[robotc]: http://www.robotc.net/download/vexrobotics/
[differences]: http://blog.alawrence.net/?p=253