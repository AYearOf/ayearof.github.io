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
(and might be for you too) read on.

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

VEX IQ bots:
<iframe width="560" height="315" src="https://www.youtube.com/embed/_9VaV5RO7TQ" frameborder="0" allowfullscreen></iframe>

EV3 Home robots
<iframe width="560" height="315" src="https://www.youtube.com/embed/uz11s_JJayM" frameborder="0" allowfullscreen></iframe>

EV3 Education robots
<iframe width="560" height="315" src="https://www.youtube.com/embed/iTH-WwrldLY" frameborder="0" allowfullscreen></iframe>


However, in looking over the instructions, I had an easier time following
VEX IQ's than EV3's. I also like the tips that you get at the beginning 
of the build instructions, e.g. 
*"Quickly remove Connector Pins by pressing a VEX IQ Beam against the back of the Pin and pulling it out"*
or *"Rubber Shaft Collars become softer and easier to install if they are warmed by holding them in your hand for 15-30 seconds"*. 

For beginners, those kind of tips can save a lot of time and frustration.

## Structural

I haven't *actually* tried the IQ set, but people with experience with both kits say
that it's **easier to build** (or rebuild) with VEX IQ. 
For one, it seems to have some larger plates and beams which should make it easier
to build larger robots.

To a [certain degree](http://www.vexforum.com/index.php/9833-compatibility-of-vex-and-vex-iq/0), 
VEX IQ is also compatible with the VEX EDR, which
would allow you to replace some of the structural 
components with stronger metal pieces from the EDR. 

On the other hand, the EV3 uses LEGO Technic pieces, which opens
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

## Electronics

### Sensors
VEX IQ comes with **more sensors** than the Home version of EV3 
and about **on par** with the Education version.  
I cannot comment on the quality of the sensors -- 
I'm going to assume they are about the same.

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
| Mechanical Power @ 4.5V, 9V, 12V | 0.43W, 1.9W, 2.77W | 0.17W, 1.15W, 1.73W | 1.4W @ ?  | 
| Output power @ 4.5V, 9V, 12V     | 3.1W, 6.21W, 8.28W | 1.57W, 3.33W, 4.44W | ?         | 
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

### Third Party

Finally, the EV3 has quite a 
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
so pretty much anything you can do on Linux, yo can do on the brick.


### Design

On the CAD front, LEGO has the [LEGO Digital Designer aka LDD][ldd],
with both OS X and Windows version;
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

There are [more competitions](http://www.robotevents.com/robot-competitions),
but the kits used are considerably above the EV3 and IQ levels.

## Final Words

W


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