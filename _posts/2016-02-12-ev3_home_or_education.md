---
layout: post
title: "Mindstorms EV3: Home or Education?"
---

Once I've settled on [using a robotics kit][roboticssets]
and have, wisely or not, [chosen the LEGO Mindstorms EV3][ev3vsiq],
I had to decide which specific version to go with, because EV3 comes in 
two flavors:

- a **retail** version, known as [EV3 Home Edition][home] 
  or #31313 by its Lego ID, a [350 USD set][ev3amz], widely available, and
- an **education** version, called [EV3 Education Core][edu],
  item #45544 (also called #5003400), a [379 USD set][edu-us],
  available only from the [LEGO Education store][edu]
  (price and availability varies by geographic region).

While the kits have an large overlap in the number of pieces,
the robots you build with them are considerably different. 

EV3 Home set robots:  
![EV3 Home set robots](/assets/ev3.jpg)

EV3 Education Core Robots:  
![EV3 Education Core set robots](/assets/ev3-robots-core.jpg)

To top it off, there's also an [Expansion set for the Education version][exp],
which allows even more robots to build.

![EV3 Expansion set robots](/assets/ev3-robots-expansion.jpg)


## Choosing

[RobotSquare has a *great* article][rs-diff] going into exquisite 
detail on how the sets compare and how do they differ.   
Their article on [which set to buy][rs-which] has been 
a source of great inspiration in my choice too. 

After *very* careful consideration, I have decided to 
purchase the Education Core set and its Expansion set as well.
Between the two of them one can build a significant number 
of very interesting robots.

However the robots from the Home set also look as if they are
a bundle of fun. This is when I decided I'd like to build them as 
well. 

Financially, it seems cheaper to purchase the Education Core set
then the pieces that differ between Education and Home then the other way
around. For one, that rechargeable battery that comes with the Core set
is both attractive and expensive.

## Upgrading Sets

RobotSquare's article on [the difference between Home and Education][rs-diff]
is a great one and you should read it, then read it again.

In it, the author also talks about upgrading from one set to the other,
and includes links to various people who have put together lists of 
parts required to complete the sets. 

Some of the links in that article are dead, and even those that 
[still work][bittner], make what I see to be a mistake: compute
the difference on exact *Part Numbers*, rather than on *LEGO Design ID*.

## Computing the Difference

The BrickWiki [explains it well][legoelementid]:

> A "Plate 2 x 3" has a LEGO Design ID of "3021".
  But for a "Dark Green Plate 2 x 3", you have a LEGO Part Number of "4297717".
  And for a "Sand Blue Plate 2 x 3", you have a LEGO Part Number of "4153276".
  So different LEGO Part Numbers for each combination, but with the same LEGO Design ID for each.

The same applies to the EV3 sets.
For example, the *Home set* uses Element ID 4111998 for
[LEGO Part 32009 - Technic Beam 1 x 11.5 Double Bent Thick](http://rebrickable.com/parts/32009)
while the *Education set* uses 4495412, 
and the *Expansion set* uses 4234240 for the same.
They are indeed different colors (black, white, and respectively gray),
but the part is the same otherwise.  
It even comes in purple (Element ID 4112277).

[![Part 32009 in black, white, gray, and purple](/assets/part32009.jpg)](/assets/part32009.jpeg)


And this is where the mistake I mentioned above comes in.  
If you compare by Element ID, which is how LEGO discloses the contents of the sets,
you might think you need to purchase
one part because it does not exist in the other set. 

<small>
And if you're a stickler for colors, that might be something
you're willing to do. Certainly all the spreadsheets and PDFs
and documents [mentioned above][rs-diff] take this route. 
</small>

However, if one was to compare by Design ID, then we'd 
see there's quite a **significant overlap** between
the Education and Home set. That means less parts we need to buy.
  
<small> Not only that, but it means we can buy them in whatever
color is the cheapest at the time on the LEGO parts sites.
</small>

To **compute the difference** I've used one of the excellent features
offered by [Rebrickable.com](http://www.rebrickable.com), which allows
you to export the parts that make up a set in 
a CSV format.

I have done so for the [Home][rebrick_31313], [Education Core][rebrick_45544],
and [Expansion set][rebrick_45560],
then imported them into [Google Docs][gsheet] where I cleaned up the data
and then ran a pivot report that grouped them by Design ID, thus
ignoring colors, and then by set, to get a cross-table 
with the number of records in each set.

This allows me to do the kind of calculations you see 
on [Comparison by Design ID worksheet][gsheet]
in column F: **45544+45560-31313** aka Core + Expansion - Home.

<iframe width="800" height="600"
  src="https://docs.google.com/spreadsheets/d/12YGMiNx-greHYJuw5uDGsZPmEQLQxy0dLbN8s0iVKeI/pubhtml?gid=1648060354&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

[Click here][gsheet] to get access to the full spreadsheet.

## Purchasing

Now that you have the minimal set of components required to translate between sets, 
you can use one of the many LEGO sites to purchase 
the missing part. 

<small>
I personally used BrickOwl
because it allowed me to create 
[a wish list with all the missing items][brickowl-list]
and its powerful calculation engine
allows me to select the combination of sellers
that yields the lower price.  
You can copy [my wish-list][brickowl-list] and use it as your own starting point.
</small>

However, even at this point there are **more money-saving
opportunities**. 

The Home version comes with some cool looking robots,
but some of the parts used are purely aesthetic;
take a look at [the "legs" of the SPIK3R robot](http://www.lego.com/en-us/mindstorms/build-a-robot/spik3r) -- 
upon closer examination you can tell that 
most of spikes, actually called
[Technic Sword 11.5L with Sawtooth Back with Flat Silver Blade](http://rebrickable.com/parts/98568p02)
and [panels](http://rebrickable.com/parts/64683) are actually non-functional.  
That means you can save some money if you don't purchase them.

Furthermore, you can also save a signficant amount
by not purchasing the [infrared sensor](http://shop.lego.com/en-US/EV3-Infrared-Sensor-45509) ($30)
and [beacon](http://shop.lego.com/en-US/EV3-Infrared-Beacon-45508) ($30)
and instead use the [ultrasonic sensor](http://shop.lego.com/en-US/EV3-Ultrasonic-Sensor-45504)
that comes with the Education set
and the free [Robot Commander App](http://www.lego.com/en-us/mindstorms/downloads/robot-commander-app/)
to achieve the same functionality.




[roboticssets]: {% post_url 2016-01-05-choice-of-robotics-sets %}
[ev3vsiq]: {% post_url 2016-01-28-mindstorms_vs_vex %}
[home]: http://shop.lego.com/en-US/LEGO-MINDSTORMS-EV3-31313
[edu]: ttps://education.lego.com/en-us/lego-education-product-database/mindstorms-ev3/45544-lego-mindstorms-education-ev3-core-set/
[edu-us]: https://shop.education.lego.com/legoed/en-US/catalog/product.jsp?productId=5003400&isSimpleSearch=false&ProductName=EV3-Core-Set-&ProductLine=LEGO-MINDSTORMS-Education-EV3 
[exp-us]: https://shop.education.lego.com/legoed/en-US/catalog/product.jsp?productId=45560 
[exp]: https://education.lego.com/en-us/lego-education-product-database/mindstorms-ev3/45560-lego-mindstorms-education-ev3-expansion-set
[ev3amz]: http://www.amazon.com/LEGO-6029291-Mindstorms-EV3-31313/dp/B00CWER3XY/?{{ site.amazontag }} "I get a small referral fee if you purchase it on Amazon through this link, so please consider doing so if you found this post useful"
[rs-which]: http://robotsquare.com/2014/11/13/ev3-home-edition-or-ev3-education-edition/
[rs-diff]: http://robotsquare.com/2013/11/25/difference-between-ev3-home-edition-and-education-ev3/
[gsheet]: https://docs.google.com/spreadsheets/d/12YGMiNx-greHYJuw5uDGsZPmEQLQxy0dLbN8s0iVKeI/edit#gid=1648060354
[brickowl-list]: http://www.brickowl.com/wishlist/view/philipmat/ev3-45544-45560-31313
[ldd]: http://ldd.lego.com/en-us/
[ldraw]: http://www.ldraw.org/
[rebrick]: http://rebrickable.com/
[rebrick_31313]: http://rebrickable.com/sets/31313-1/mindstorms-ev3-ev3-2013 
[rebrick_45544]: http://rebrickable.com/sets/45544-1/ev3-core-set-ev3-2013
[rebrick_45560]: http://rebrickable.com/sets/45560-1/ev3-expansion-set-ev3-2013
[bittner]: https://github.com/bittner/lego-mindstorms-ev3-comparison
[legoelementid]: http://www.brickwiki.info/wiki/Element_ID
