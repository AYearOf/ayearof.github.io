---
title: Choice of Robotics Sets
---

The first choice I had to make in pursuing my [Year or Hobbies: Robotics][hobbies2016] 
was which direction to go in? The choices are threefold: already built robots — 
leaning more towards programming (eg OWI) robotics kits (Mindstorms, VEX), 
or the free-form route of Arduino (or RaspberryPi). 

Here are my constraints:

- Multi-function: if they only did one thing, 
  it would be pretty boring no matter how well they do that one thing;
- Programmable: I want my labyrinth solver to figure out the path by itself;
- Not overly complex: it's a hobby, so satisfaction should be achievable 
  without heroic efforts; additionally, I'd like to be able to bring 
  my 12-year old step-daughter into these adventures;
- Should allow for learning something new, yet be focused at the same time: 
  I don't want to have to juggle 3+ disciplines at the same time 
  (and programming is already a must-have)

## Already Built Robots
Great choice if the intent is to lean more towards the controlling side.
Some offer programming possibilities. 

For example, [Ozobot Bit](http://ozobot.com/products/ozobot-bit) looks like a blast 
if you want to built a follow-the-line bot.
 
[![Ozobot Bit](/assets/ozobit-640.jpg)](http://ozobot.com/products/ozobot-bit)

[OWI Robotics](http://www.owirobot.com) also seem to have great resources at great prices: 
from the robotic arm to the solar kits, they're all getting excellent reviews. 

On the downside, their fixed shape constrains how much you can do with them. 
It might be difficult to build a roaming robot out of the fixed robotic arm, 
but maybe that's just my imagination lacking.

# Robotics Kits

The beginner robotics systems have long been dominated by [LEGO Mindstorms][ev3]. 
In this world, [VEX Robotics][vex] is a new entrant, 
but they did do a great job building an environment to rival LEGO’s. 
They have not one, but three levels of sets: [VEX IQ][vexiq], 
[VEX EDR][vexedr], and VEX PRO.

[![LEGO Mindstorms EV3](/assets/ev3.jpg)][ev3]

[VEX IQ][vexiq] seems a direct competitor to the [LEGO Windstorms EV3][ev3] set. 
Both feature similar looking plastic pieces, with wheels, axles, etc. The price 
of the base kit is below that of the EV3, but it's not the only items that makes
it attractive as a starter kit. 
[![VEX IQ](http://content.vexrobotics.com/images/landing/VEX_IQ_Tile_5.png)][vexiq]

[VEX EDR][vexedr] is a step-up version, with a great deal of configuration options, 
sporting metal structural parts, and a multitude of sensors, motors, gears,
and wheel. At least to me, the kits feels obviously aimed towards serious 
hobbyists, higher education, and FRC (FIRST Robot Competition) teams.

[![VEX EDR](http://content.vexrobotics.com/images/landing/VEX_EDR_Tile_4.png)][vexedr]

I'll be writing a separate post to compare VEX IQ and EV3, 
but I would have *no problem* recommending the VEX IQ over EV3 
for anybody interested in pursuing robotics as a hobby. For one, 
EV3 is technically limited upwards by its reliance on Technic parts,
which at the end of the day are plastic parts - I doubt that one will
be able to win a BattleBots/Robot Wars/RFL (Robot Fighting League) competition 
with a Mindstorms robot, or build any heavy-lifting mechanisms.

Conversely, one can start with VEX IQ and graduate step by step into
VEX EDR and then into the VEX PRO.  

However, for my own needs, I decided the EV3 kit was more than sufficient. 
Furthermore, the ability to connect the Technic parts with regular LEGO parts
should [yield some fun builds][robots].

## DIY - All of It

At the opposite end of the already built robots stands the world of Arduino and, 
to a larger extent, RaspberryPi (it seems Arduino is a [better choice for task-oriented systems][arduino-vs-rpi], 
while RaspberryPi for longer-running systems).

And that's a *beautiful* thing. 
You start from the core components and add only what you need: 
servos, sensors, etc. 
You buy only what you need, thus not only keeping the costs to a minimum, 
but you have the ability to select the best suited components, of which 
there are plenty.

The support is spectacular, both on the hardware and on the software side.

The amount of fabrication tends to be larger than in the Mindstorms/VEX case. 
You need to hand build all the frames you need for your robots, 
although you can get reasonably far with pre-build chassis for wheeled robots; 
something like the [Track3r][track3r] might not take a lot, 
while I wouldn't even know where to start for the [R3ptar][r3ptar]. 
On the flip side, you can build considerably larger and stronger robots 
than you can with LEGO. 

You will also have to learn, if you don't know already know, 
a good deal about electronics and electric circuitry. 
While I do have a BS in Computer Science & Electrical Engineering, 
I remember none of it, and to be honest it seemed a bit more than 
I wanted to *start* with.

That doesn't mean Arduino will not part of my world - 
I can already see it showing up in some support scenarios,
for example I want to build a better [line following robot][line-robot], 
one that [also obeys traffic lights][line-robot-traffic]; 
those traffic lights will likely be built using an Arduino kit.

## TL;DR

To recap, I've decided to go the route of LEGO Mindstorms EV3, 
due to its lack of complexity, programmability, and extensibility 
(not too much, yet enough for a year).


[hobbies2016]: /2016/index.html
[arduino-vs-rpi]: http://makezine.com/2013/04/15/arduino-uno-vs-beaglebone-vs-raspberry-pi/
[track3r]: http://www.lego.com/en-us/mindstorms/build-a-robot/track3r
[r3ptar]: http://www.lego.com/en-us/mindstorms/build-a-robot/r3ptar
[line-robot]: /2016/line_following_robot.html
[line-robot-traffic]: /2016/line_following_robot-version_2.html
[ev3]: http://shop.lego.com/en-US/LEGO-MINDSTORMS-EV3-31313
[vex]: http://www.vexrobotics.com/
[vexiq]: http://www.vexrobotics.com/vexiq?ref=hometile
[vexedr]: http://www.vexrobotics.com/vexedr?ref=hometile
[robotc]: http://www.robotc.net/download/vexrobotics/
[differences]: http://blog.alawrence.net/?p=253
[robots]: /2016/list_of_goals.html