---
layout: post
title: Mindstorms EV3 vs VEX IQ
---
Let me give you the TL;DR right off the bat: 
if you plan on doing robotics, 
buy the [VEX IQ Super Kit](http://www.vexrobotics.com/vexiq/products/kits-bundles/super-kit.html). 

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
(and might be for you too) read on. If not, at least
read [Damien Kee's comparison][ev3vsiq] for a 20,000-foot 
overview.


## Set Contents

Out of the entire VEX line, [VEX IQ][iq] seems a direct competitor to the 
[LEGO Mindstorms EV3][ev3] set.

Both feature similar looking plastic pieces, with wheels, axles, etc.  
Both feature some sort of "brain" for the robot, aka programmable "brick",
sensors, motors, wheels, gears, and a plethora of structures to build
the frame of your robot. However, they are in no way compatible with 
each other and thus no parts can be interchanged between the sets.

EV3 comes in two separate versions. The Home or Retail version is the 
version you can pick up in stores at Toys'R'Us or [on Amazon][ev3amz]; 
the Education version, called [Education Core Set](https://education.lego.com/en-us/lego-education-product-database/mindstorms-ev3/45544-lego-mindstorms-education-ev3-core-set/), 
needs to be [ordered online from the LEGO education store](https://shop.education.lego.com/legoed/en-US/catalog/product.jsp?productId=5003400&isSimpleSearch=false&ProductLine=LEGO-MINDSTORMS-Education-EV3), 
which by the way, seems to be 
a separate entity from the main LEGO entity.

The two EV3 sets have [some differences](/ev3-retail-vs-education.html) in included components, and the robots
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
| Sensors - Rotation   | 0                                          | 1                                          | 1                                      | 
| Brain                | ARM 9                                      | ARM 9                                      | [TI Tiva ARM Cortex-M4][tiva]          | 
| IO Ports             | 4 in, 4 out                                | 4 in, 4 out                                | 12, self-detecting                     | 
| Brain Interface      | USB, BT, MicroSD, (can attach WiFi dongle) | USB, BT, MicroSD, (can attach WiFi dongle) | USB                                    | 
| Controller           | IR Remote or iOS and Android apps          | IR Remote or iOS and Android apps          | Video-game like, available separately  | 
| Power                | 6 x AA                                     | 2050 mAh LiIon battery                     | 2000 mAh NiMH rechargeable             | 
| Software             | LEGO Mindstorms based on LabView           | LEGO Mindstorms / LabView                  | [Modkit for VEX][mk], a Scratch-like environment, or [RobotC for VEX][rcv], a C-like programming language | 
| Storage              | No                                         | Yes                                        | Yes                                    | 
| Price                | $349                                       | $349                                       | $249                                   | 


For the most part, you can tell from the table above that the VEX IQ is a better deal.


## Robots and Instructions

![EV3 vs VEXIQ](/assets/ev3-iq-robots.jpg)

All three kits have about the same number of robots that can be built out of the box with the starter kit, 
but within those robots there seem to be more variations on the EV3 side:
the EV3 instructions for a given robot also offer adaptations 
in sensors and secondary attachments; it makes it easier to build 
a robot with slightly different abilities while keeping 98% of the frame
already built.

On a personal level, I feel that the robots you build with the EV3 set,
both Retail and Education, are better looking than the robots you build
with IQ set (I think [HEXBUG][hexbug] is trying to fix some of this).
While that might sound shallow, consider that if you have
kids involved, having cool robots is a significant plus.

Who could resist the adorable Puppy robot (Education set)? 

<iframe width="560" height="315" src="https://www.youtube.com/embed/zriGyLddpBQ" frameborder="0" allowfullscreen></iframe>


However, in looking over the instructions, I had an easier time following
VEX IQ's than EV3's. I also like the tips that you get at the beginning 
of the build instructions, e.g. 
*"Quickly remove Connector Pins by pressing a VEX IQ Beam against the back of the Pin and pulling it out"*
or *"Rubber Shaft Collars become softer and easier to install if they are warmed by holding them in your hand for 15-30 seconds"*. 

For beginners, those kind of tips can save a lot of time and frustration.


### VEX IQ bots
<iframe width="560" height="315" src="https://www.youtube.com/embed/_9VaV5RO7TQ" frameborder="0" allowfullscreen></iframe>


### EV3 Home robots
<iframe width="560" height="315" src="https://www.youtube.com/embed/uz11s_JJayM" frameborder="0" allowfullscreen></iframe>


### EV3 Education robots

I couldn't find a video of all the robots you can build with 
the Education set, so here is collage of the various robots.

With the Education core set:
[![EV3 Education Core robots](/assets/ev3-robots-core.jpg)](/assets/ev3-educore-robots-large.jpg)

Once you add With the Education expansion set:
[![EV3 Education Expansion robots](/assets/ev3-robots-expansion.jpg)](/assets/ev3-eduexp-robots-large.jpg)

The presence of instructions is an individual preference,
but all else being equal I'd rather have more instructions 
and not use them. In this, the EV3 sets do a great job.


## Structural Components

I haven't *actually* tried the IQ set -- I'm relying on information from friends and the web -- 
but people with experience with both kits say
that it's **easier to build** (or rebuild) with VEX IQ. 
For one, it seems to have some larger plates and beams which should make it easier
to build larger robots. The IQ set has **thinner pieces** that require more bracing,
but they also allow bending, which would expand the range of possibilities.

To a [certain degree](http://www.vexforum.com/index.php/9833-compatibility-of-vex-and-vex-iq/0), 
VEX IQ is also compatible with the VEX EDR, which
would allow you to replace some of the structural 
components with stronger metal pieces from the EDR. 

On the other hand, the EV3 uses **LEGO Technic pieces**, which opens
the door to a whole large world of kits and builds, including
the possibility of automating some of the Technic sets.  
Mmmm [Container Truck][tekcontainer] + [Volvo Loader][tekvolvo]... 
...I'll be in my bunk.

![EV3 vs VEX IQ - Structural Elements](/assets/ev3-iq-struct.jpg)

Furthermore, one can also add regular LEGO blocks in the mix,
which is a ridiculous reason to pick the EV3 over 
the IQ, but it might allow you to include younger 
children into your building activities.

The Education set also comes with one interesting part: a **ball-wheel**;
it makes it easy to build robots that can turn using only 
two motors for the driving wheels as the ball-wheel would
serve as the third, non-powered wheel.

![EV3 Education - Ball Wheel](/assets/ev3-ball-wheel.jpg)


### Gears

When it comes to gears, it becomes a bit more difficult to make a straight comparison.

The VEX IQ feels like it has the upper hand with a host of regular gears,
from [12 to 60 teeth](http://www.vexrobotics.com/vexiq/products/accessories/motion/iq-gear-g.html) in a variety of colors,
to [sprockets and chains](http://www.vexrobotics.com/vexiq/products/accessories/motion/iq-chainsprock-g.html),
to [racks, worms, and slides](http://www.vexrobotics.com/vexiq/products/accessories/motion/228-2532.html),
to [differentials](http://www.vexrobotics.com/vexiq/products/accessories/motion/differential-and-bevel-gear-pack.html).

The EV3 has a similar range of gears (from 8 to 40 teeth), sprockets, racks, etc,
but also includes a slightly different take on [turntable gears](http://www.amazon.com/LEGO-Technic-Turntable-Platform-Gear/dp/B0040DLAIY?{{ site.amazontag }}):
whereas the IQ is smooth and ball-bearing, the LEGO variant has teeth so it can be used
both as a turntable and as a reduction gear. I feel the 
[sprockets and chains](http://www.vexrobotics.com/vexiq/products/accessories/motion/iq-chainsprock-g.html) are better
in the VEX IQ are better than the LEGO equivalent and there's a 
a better set of [pulleys](http://www.vexrobotics.com/vexiq/products/accessories/motion/iq-pulley-g.html) too. 

Worth mentioning that with the EV3 you have access to the full set of Technic gears
(read [Sariel's tutorial on the topic][sariel_gears]).


### Wheels

Except for [VEX IQ's cool omni-directional wheel](http://www.vexrobotics.com/vexiq/products/accessories/motion/228-2536.html),
the EV3 has the upper hand not only by what's included in the starter kits --
that part is on par with the IQ --
but by the [sheer number of wheels and tires](http://www.amazon.com/LEGO-Education-Wheels-4598357-Pieces/dp/B004HXCX3I?{{ site.amazontag }}) 
combinations available from the Technic sets, all of which are usable with the Mindstorms set.


## Electronics

The two sets offer the same type of electronics and with very similar specs,
with VEX IQ's offer being slightly better in motors. Similar to the motors,
the VEX IQ sensors seem to be smaller in size, which does help in almost any
construction you plan on building.


### Brick

The brain, aka controller aka brick, is where they differ significantly.

The VEX IQ has **12 auto-sensing I/O ports**, meaning you can 
connect as many motors or sensors as you want, 
in any combination you want,
whereas the EV3 has **4 dedicated motor ports and 
4 dedicated sensor ports** -- meaning that if you 
need to connect 5 motors you need to look at the 
3rd party market for a *motor multiplexer* -- 
[$55 for 2 extra motor ports][multiplex].

However, the VEX IQ is based on [TI Tiva ARM Cortex-M4 Processor][tiva], 
with only 256K flash and 32K RAM, about the same as the old Mindstorms NXT.

The [EV3 brick][ev3brick] uses a much faster 
[TI Sitara ARM 9 processor](https://en.wikipedia.org/wiki/Sitara_ARM_Processor) -- 
the same as the Nintendo DS, NEST Thermostat, or [BeagleBone Black](http://www.amazon.com/BeagleBone-Black-Single-Computer-Development/dp/B00LC1924G/?{{ site.amazontag }}) --
with 16 MB of Flash memory, 64 MB of RAM, and running at 300MHz. This has some exciting
ramifications, which we'll talk about in the Software section.


EV3 Brick allows display of images, can play sounds, and change LED color.
It's not backlit. IQ is. 

From a connectivity perspective, the EV3 is better equipped 
out of the box: both use USB to upload programs to the brick,
but the EV3 also comes with Bluetooth, which allows you
to [control your robot using your iOS or Android phone](http://www.lego.com/en-us/mindstorms/downloads/robot-commander-app/).

The VEX IQ comes with a 900 MHz radio module that talks to their
[game-like controller][iqctrl]; for only $13 you can purchase a 
[Smart Radio module][vexbt]
that enables Bluetooth 4.0 connection to the brick,
and theoretically would enable the creation of a similar
controller app (there is none available at the moment).


### Motors

VEX IQ comes with **4 motors** and the EV3 sets come with **1 medium and 2 large motor**.   
The medium-sized EV3 motor is a higher rpm, lower torque motor; 
the large EV3 and VEX IQ motors are lower rpm but higher torque. 

![EV3 vs IQ motors](/assets/ev3-iq-motors.jpg)

| Parameter                        | EV3 Large (#45502) | EV3 Medium (#45503) | VEX IQ    | 
|----------------------------------|--------------------|---------------------|-----------| 
| Servo?                           | Y                  | Y                   | (1)       | 
| Encoder accuracy                 | 1 deg (2)          | 1 deg (2)           | 0.375     | 
| No-load RPM                      | 160-170            | 240-250             | 120       | 
| No-load current                  | 60mA               | 80mA                | ?         | 
| Running torque                   | 20 N/cm = 30 oz/in | 8 N/cm = 11oz/in    | ?         | 
| Stall torque                     | 40 N/cm = 60 oz/in | 12 N/cm = 17 oz/in  | 41.4 N/cm | 
| Stall current                    | 1.8A               | 780 mA              | [1.1 @ 7.2V](http://www.vexiqforum.com/forum/main-category/main-forum/9393-validating-component-goodness-for-reuse-next-year?p=9864#post9864)| 
| Sample/Command rate              | 1 kHz (3)          | 1 kHz (3)           | 3 kHZ     | 
| Mechanical Power @ 4.5V, 9V, 12V | 0.43W, 1.9W, 2.77W | 0.17W, 1.15W, 1.73W | ?         | 
| Output power @ 4.5V, 9V, 12V     | 3.1W, 6.21W, 8.28W | 1.57W, 3.33W, 4.44W | 1.4W @ ?  | 
| Weight                           | 82g                | 39g                 | ?         | 
| Size (4)                         | Large              | Medium              | Small     | 
| Price                            | $25                | $20                 | $20       | 

Notes:

- (1): The VEX IQ motor doesn't seem to be a proper servo 
  (a servo will move to a position then attempt to hold that position, even without power), 
  but it seems it can be made to hold its position under active power;
- (2): EV3 encoding accuracy can be doubled to 0.5 degrees 
  [with a small hack](https://en.wikipedia.org/wiki/Lego_Mindstorms_EV3#Enhancements)
- (3): I cannot find any information about EV3 motor command rates, 
  but the sample rate for the rest of the sensors seems to be 1 kHz,
  so I'll assume to be the same for the motors;
- (4): The smaller physical size of the VEX IQ engine means that it can be used in more compact builds,
  or in tighter spaces; the larger size of the EV3 motors means
  it can be part of your structure or structural reinforcement.

Thanks to Philippe "Philo" Hurbain for a lot of the [research into Technic motors][technicmotorcomparison]!


### Sensors

VEX IQ comes with **more sensors** than the Home version of EV3 
and about **on par** with the Education version.  

[![EV3 vs IQ sensors](/assets/ev3-iq-sensors.jpg)](/assets/ev3-iq-sensors.jpeg)


### Gyro Sensors

Much like the rest of the narrative,
the [VEX IQ Gyro](http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-3014.html)
is both a better and a little bit worse than the
[EV3 Gyro sensor #45505](http://shop.lego.com/en-US/EV3-Gyro-Sensor-45505).


| Parameter   | EV3 #45505         | VEX IQ  |
|-------------|--------------------|---------|
| Sample rate | 1 kHz              | 3 kHz   |
| Accuracy    | +/- 3 degrees      | ? (1)   |
| Max output  | 440 degrees/second | 550 degrees/second |
| Price       | $30                | $25     |

- (1) There's no information about the accuracy 
  of the IQ gyro sensor, but a post in the forus
  mentions [1 deg/minute drift in reading](http://www.vexiqforum.com/forum/main-category/official-answers-ask-the-vex-staff/7409-code-for-driver-control-program).
  Perhaps the EV3 has [the same issue](http://forums.usfirst.org/showthread.php?20801-EV3-Gyro-sensor-drift), 
  but it's somehow [eliminated in software](http://stemrobotics.cs.pdx.edu/node/2887).


### Distance Sensors

There are two types of distance sensors: ultrasonic and infrared.

The ultrasound sensor tends to be more precise at larger distances,
but due to its nature it suffers when the reflecting surface is sub-optimal:
curved surfaces and smooth surfaces at skew angles deflect the signal away from the receptor in the sensor;
cloth and carpet-like surfaces, including drapes, allow the signal to pass through and reflect very little back.  

In contrast, the infrared sensor works off reflecting light so it suffers 
less from these issues, however it has its own set of problems, the main
one being light polution causing the sensor to only be effective at 
short distances.

Both types of sensors have an active scanning mode and 
passive receiving mode enabling the infrared sensor to act
as a receiver for a remote, e.g. 
[EV3 Infrared beacon](http://shop.lego.com/en-US/EV3-Infrared-Beacon-45508),
whereas the ultrasonic sensor can act as a noise detector.   

[![EV3 IR beacon and sensor](/assets/ev3-ir.jpg)](/assets/ev3-ir.jpeg)

The [VEX IQ Distance sensor](http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-3011.html)
is ultrasonic, similar to the 
[EV3 Education kit's distance sensor](http://shop.lego.com/en-US/EV3-Ultrasonic-Sensor-45504);
The EV3 Home version comes instead with [an Infrared sensor](http://shop.lego.com/en-US/EV3-Infrared-Sensor-45509)
(pictured above).

It's worth pointing out that the eye-like construction of the ultrasonic 
sensor, with an emitter and a receiver side by side, causes 
detection bias towards the side with the transmitter.  

| Parameter   | EV3 Ultrasonic #45504   | EV3 Infrared #45509 | VEX IQ                 |
|-------------|-------------------------|---------------------|------------------------|
| Range       | 1-250 cm = 1-100 in     | 50-70 cm = 20       | 1-300cm = 1-120 in (1) | 
| Accuracy    | +/- 1 cm = +/- 0.394 in | ?                   | ?                      |
| Receive Mode| Yes                     | Yes (2)             | ?                      |
| Price       | $30                     | $25                 | $25                    |

- (1) marketing copy; after it was pointed that max distance [seems to be 610mm in RobotC and 500mm in ModKit](http://www.vexiqforum.com/forum/main-category/technical-discussion/1437-distance-sensor?p=1449#post1449),
  in an email exchange with a support person, VEX recognized 
  that they need to update the web page to read a 2 to 18 *usable* distance,
- (2) - up to 2 meter = 6 feet distance from beacon

### Color Sensors

The kits come with sensors capable of detecting multiple colors, but also 
measure relative ambient light level (comes in handy for follow-the-line robots).

The [VEX IQ color sensor](http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-3012.html)
is the superior one here:  

- can detect 12 simple colors:
  red-violet, red, dark-orange, orange, dark yellow, yellow, lime green, green, blue-green, blue, dark blue, violet;
- RGB - 256 levels each;
- senses color hue;
- ambient light level;
- costs $25 (comes in the kit, but for replacement purposes...).

[The EV3 color sensor](http://shop.lego.com/en-US/EV3-Color-Sensor-45506) costs $40 for a replacement,
and has lower spects on the detection level:

- only 8 colors: black and white (1), or between blue, green, yellow, red, white and brown;
- samples at 1 kHz;
- can detect ambient light level.

**Note (1)** - professing color detection of black and white seems a bit
like cheating in specs, as I'm sure the VEX IQ detects the same. That 
would put the IQ sensors at 14 colors vs 8 for the EV3.


### Bump aka Pressure Sensors

There are bump sensors in both kits and they function the same; they take
a low pressure to trigger and can register three states: pressed, released,
and "bumped" (quick press followed by release). In both cases you can 
attach other elements to them, e.g. a cross-axle, to perhaps increase their range.

It's puzzling though why the 
[VEX IQ bump sensor](http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-2677.html)
costs only $5 while the [EV3 bump sensor](http://shop.lego.com/en-US/EV3-Touch-Sensor-45507)
costs $20 - *four times the price*.

Note that the EV3 refers to the sensor as a "touch sensor",
but in the context of modern parlance where touch typically
means *capacitive* touch sensor, I feel bump sensor is a less
ambiguous name.


### LED Signaling

In terms of signaling, the EV3 relies on the brick: 
it can display text and images, but you can also 
program the LEDs surrounding the control buttons
to change to one of three colors: green, amber, red,
and to blink at various rates.

In contrast, the VEX IQ set offers a combination 
[Touch sensor with LED](http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-3010.html)
that is truly touch-triggered, but it can also 
use the embedded LED lights to display some 16 million color variations,
in addition to being able to blink at specified rates.

[![VEX IQ touch sensor with LED](/assets/vexiq-touch.jpg)](/assets/vexiq-touch.jpeg)

Offering a separate LED signaling device means 
that not only it can be placed in a prominent place,
but that **more than one** can be attached to the controller.


### Cables

Both kits use, apparently [for safety reasons](http://www.philohome.com/nxtplug/nxtplug.htm),
proprietary connectors on their cables. They are modeled after 
[a 6P6C plug](https://en.wikipedia.org/wiki/Modular_connector#6P6C) (telephone plug),
but the EV3's latch is right-offset, whereas the VEX IQ is left-offset.

I really wish they had use the same connector, because unsurprisingly
the VEX IQ cables are cheaper than the EV3: 
[$10 for 6 cables](http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-2780.html)
vs 
[$15 for 7 cables](http://shop.lego.com/en-US/EV3-Cable-Pack-45514).

Both sets have extra long cables (1-2 m = 3-6 ft) available for purchase,
through [VEX Robotics](http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-4422.html)
in the IQ case, and [3rd parties](http://www.mindsensors.com/51-cables-connectors) in the EV3 case.


### Third Party

Finally, the EV3 shines in that it has quite a 
[rich][mindsensorsev3] 
[3rd-party][robotshopev3]
[parts][genrobot] market - 
there's even a RaspberryPi replacement for the brick: 
[BrickPi](http://www.dexterindustries.com/brickpi/) 
(and a not-too-expensive [BrickPi Starter Kit][brickpikit]).  
VEX Robotics is currently the only supplier for 
VEX IQ, but they have good offerings at *very* sensible prices.


## Software

There are two dimensions to consider when it comes to the software 
part of your robot: by far the more important is the programming 
part, but being able to design and share your designs with others
is something communities thrive on.

To be honest, in terms of features and pricing, EV3 has the upper hand.  
By a wide margin.


### Programming

The default programming environment for the EV3 
is LabView-based, using a metaphor of various types
of blocks to represent sensors, actions (motors, speaker),
data operations (on variables), instructions (loops, etc),
and some advanced blocks (manage files, BT, system). 
It also comes in two versions, 
a Home version and an Education version, both free, purposefully 
mirroring the two EV3 sets because each version builds
robots specific to the parts that come with the respective sets.  
This software is available for [OS X and Windows](http://www.lego.com/en-us/mindstorms/downloads/download-software),
and there's also a version of the software for [iOS and Android](http://www.lego.com/en-us/mindstorms/apps/ev3-programmer-app),
although the latter has some limitations in what blocks it can use.

![EV3 Software](/assets/ev3-software.jpg)

The apps, in all their variants contain both step-by-step building 
instructions, as well as the programming environment. 

The VEX IQ has three options, *none which are free*,
from $50 for [ModKit][mk], a Scratch-like visual language (Windows & OS X),
to $75 for [easyC][easyc], which is a more typical programming language (Windows only),
to $80 for [RobotC for VEX][rc], which supports both approaches, 
but it's also Windows only. 

Due to the considerably larger memory of the EV3 brick and the microSD port,
it's possible to actually run a full-blown distribution of Linux
on the brick; [ev3dev][ev3dev] is one such distro that ships
with **full version of Python**, including the modules
and libraries necessary to program your robots. 

Then there's [LeJos][lejos] - Java based, a veteran in the field of Mindstorms programming
going back to the NXT days; and there's even a [RobotC version for EV3](http://www.robotc.net/download/lego/) 
(unfortunately it's Windows-only).  
Again, you have a full-blown version of Linux, 
so pretty much anything you can do on Linux, you can do on the brick.

One interesting sofware component that the EV3 set comes with,
although only in the Education set, is a datalog block.

This allows the brick to record high-sample sensor data, for example
data from [a temperature sensor](https://shop.education.lego.com/legoed/en-US/catalog/product.jsp?productId=9749&ProductName=MINDSTORMS-Temperature-Sensor&ProductLine=LEGO-MINDSTORMS-Education-EV3),
or truly [any of the other sensors](http://www.afrel.co.jp/en/archives/839).  
The data can be obtained and viewed in the LEGO Mindstorms app 
either on the fly, when the brick is connected to the computer,
or at a later time.

![EV3 Data Logging - chart](/assets/ev3-data-logging.jpg)


### Design

On the CAD front, LEGO has the [LEGO Digital Designer aka LDD][ldd],
a well liked program, with both OS X and Windows version, 
although [it's being discontinued](http://brickset.com/article/18789) as of January 2016;
there's even an open standard for LEGO CAD programs, [LDraw](http://www.ldraw.org),
and [quite the list of programs][ldraw] that can use it.
 
VEX IQ has [SnapCAD](http://www.vexrobotics.com/vexiq/software/snapcad) -- 
but it's Windows-only. I guess sharing designs is not that big of an issue 
with VEX IQ users.


## Competitions

This is based on pure observation, but robotics competitions
seem to be either dedicated to a certain vendor's wares, 
or more generic robotics competition that favor custom 
builds and custom programming.

LEGO has [FIRST LEGO League Jr](http://www.firstinspires.org/robotics/flljr),
[FIRST LEGO League](http://www.firstinspires.org/robotics/fll), 
and [SuGO - LEGO Sumo](http://www.sugobot.com).

VEX IQ has the [VEX IQ Challenge](http://www.robotevents.com/robot-competitions/vex-iq-challenge),
but it also seems to be the kit of choice for middle and high-school competition.   
2015–2016's [Bank Shot challenge](http://www.vexrobotics.com/vexiq/competition/competition-resources)
looks like a lot of fun.

There are [more competitions](http://www.robotevents.com/robot-competitions),
but the kits used seem considerably above the EV3 and IQ levels.


## Final Words

Between included components and low prices, 
VEX IQ feels like the right generation platform
for entry-level robotics education or competitions.

The EV3 is a power house when it comes to processing 
capacity and the availability of components,
both in loans from the Technic sets 
as well as third parties like Mindsensors or RobotShop.

As a software engineer doing this for fun, 
the processing power available to the EV3 brick 
was ultimately more attractive to me than 
the benefits offered by the [VEX IQ set][iq]. 

Stay tuned for a post on which of the EV3 sets
I decided to go with and why.  



[iq]: http://www.vexrobotics.com/vexiq
[iqctrl]: http://www.vexrobotics.com/vexiq/products/accessories/electronics/vex-iq-controller.html
[edr]: http://www.vexrobotics.com/vexedr
[iqstarter]: http://www.vexrobotics.com/vexiq/products/kits-bundles/starter-kits/
[ev3]: http://www.lego.com/en-us/mindstorms/products/31313-mindstorms-ev3
[mk]: http://www.modkit.com/vex
[rc]: http://www.robotc.net/download/vexrobotics/
[easyc]: https://intelitek-shop.com/product_info.php/cPath/2_50/products_id/161
[tiva]: http://www.vexrobotics.com/brain-g.html
[roboticssets]: {% post_url 2016-01-05-choice-of-robotics-sets %}
[hassen]: http://www.teamhassenplug.org/ev3_vexiq.html
[tekvolvo]: http://www.amazon.com/LEGO-Technic-42030-Remote-Controlled/dp/B00HR1M8KK/?{{ site.amazontag }}
[tekcontainer]: http://www.amazon.com/LEGO-TECHNIC-Container-Truck-8052/dp/B003F7WOFO/?{{ site.amazontag }}
[multiplex]: http://www.mindsensors.com/ev3-and-nxt/21-multiplexer-for-nxtev3-motors
[mindsensorsev3]: http://www.mindsensors.com/37-ev3-and-nxt
[robotshopev3]: http://www.robotshop.com/en/catalogsearch/result/?q=ev3&order=stats_sales_order_count&dir=desc
[genrobot]: http://www.generationrobots.com/en/182-lego-mindstorms-accessories
[ev3brick]: http://shop.lego.com/en-US/EV3-Intelligent-Brick-45500
[ev3dev]: http://www.ev3dev.org
[lejos]: http://www.lejos.org/ev3.php
[vexbt]: http://www.vexrobotics.com/vexiq/products/accessories/electronics/228-3530.html
[iqbots]: https://youtu.be/_9VaV5RO7TQ?list=PLvvcc7S26YEgp60fNJwh64aj9ywiZ79Ta
[ev3robots]: https://youtu.be/uz11s_JJayM
[ev3robotsedu]: https://youtu.be/iTH-WwrldLY
[technicmotorcomparison]: http://www.philohome.com/motors/motorcomp.htm
[ldd]: http://ldd.lego.com/en-us/
[ldraw]: http://www.ldraw.org/downloads-2/third-party-software.html
[ev3amz]: http://www.amazon.com/LEGO-6029291-Mindstorms-EV3-31313/dp/B00CWER3XY/?{{ site.amazontag }} "I get a small referral fee if you purchase it on Amazon through this link, so please consider doing so if you found this post useful"
[brickpikit]: http://www.amazon.com/Dexter-Industries-BrickPi-Starter-Bundle/dp/B00HJ7TSXC/?{{ site.amazontag }}
[ev3vsiq]: http://www.damienkee.com/home/2014/10/17/lego-ev3-vs-vex-iq.html
[ev345544robots]: http://robotsquare.com/2013/10/01/education-ev3-45544-instruction/
[sariel_gears]: http://sariel.pl/2009/09/gears-tutorial/
[hexbug]: https://www.hexbug.com/vex/