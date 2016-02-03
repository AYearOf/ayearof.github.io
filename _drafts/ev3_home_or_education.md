---
layout: post
title: Mindstorms EV3: Home or Education?
---

Once I've settled on [using a robotics kit][roboticssets]
and have, wisely or not, [chosen the LEGO Mindstorms EV3][ev3vsiq],
I had to decide which kit to go with, because EV3 comes in 
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

I'm not going to go into great detail about how the sets compare.

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

Laurens's article on [the difference between Home and Education][rs-diff]
is a great one and you should read it, then read it again.

In it, he/she also talks about upgrading from one set to the other,
and includes links to various people who have put together lists of 
parts required to complete the sets. 

Some of the links in that article are dead, and of those that still
work, all of them make what I see to be a mistake: compute
the difference on exact part IDs, rather than on LEGO Design Id.

Allow me to explain.

## Computing the Difference

A LEGO piece may have more than one ID. There's an ID called LDD??ID
which identified the shape piece: e.g. 1x7 beam; 1x7 beams with different
colors will have different part ids - they are identical in every other way
but the color. 

??Example??

And this is where the mistake I mentioned above comes in.  
The Home set might have a 1x7 beam in white, while the 
Education version might have the exact same beam in gray.  
If you compare by part ID, you might think you need to purchase
the part because it does not exist in the other set.

And if you're a stickler for colors, that might be something
you're willing to do. Certainly all the spreadsheets and PDFs
and documents mentioned above take this route. 

However, if one was to compare by LDD ID, then we'd 
see there's quite a significant overlap between
the Education and Home set. That means less parts we need to buy.

Not only that, but it means we can buy them in whatever
color is the cheapest at the time on the LEGO parts sites.

What I've done is to use one excellent feature
of [the Rebrickable site][rebrick] that allows
you to export the parts that make up a set in 
a CSV format.

I have done so for the Home, Education Core, and Expansion set,
then imported them into Google Docs where I cleaned up the data
and then ran a pivot report that grouped them by LDD Id, thus
ignoring colors, and then by set, to get a cross-table 
with the number of records in each set.

This allows me to do the kind of calculations you see 
in column F: Core + Expansion - Home.

## Purchasing

Now that you have the minimal set of components, 
you can use one of the many LEGO sites to purchase 
the missing part. I personally used BrickOwl
because it allowed me to create a wish list with 
all the items and its powerful calculation engine
allows me to select the combination of sellers
that yields the lower price.  
However, even at this point there are more money-saving
opportunities. 

The Home version comes with some cool looking robots --
take a look at the [spikes on the SPIK3R robot]() -- 
but upon closer analysis you can tell that 
most of spikes and panels are actually non-functional.  
That means you can save some money by not purchasing them.


















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
[gsheet]: https://docs.google.com/spreadsheets/d/12YGMiNx-greHYJuw5uDGsZPmEQLQxy0dLbN8s0iVKeI/edit?usp=sharing
[brickowl-list]: http://www.brickowl.com/wishlist/view/philipmat/ev3-45544-45560-31313
[ldd]: http://ldd.lego.com/en-us/
[ldraw]: http://www.ldraw.org/
[rebrick_31313]: http://rebrickable.com/sets/31313-1/mindstorms-ev3-ev3-2013 
[rebrick_45544]: http://rebrickable.com/sets/45544-1/ev3-core-set-ev3-2013
[rebrick_45560]: http://rebrickable.com/sets/45560-1/ev3-expansion-set-ev3-2013
[bittner]: https://github.com/bittner/lego-mindstorms-ev3-comparison
