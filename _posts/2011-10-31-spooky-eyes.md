---
title: Spooky eyes
description: Halloween Fun
category: Electronics
categories:
- avr
- electronics
image: /assets/images/normal/2011/10/img_3800.jpg
image-caption: test image caption
type: post # used in _layouts/posts.html:section
# Note: layout type of files in '_posts' is configured as 'post' in _config.yml
---
With Halloween approaching it was time to look for a little project. I came across <a title="Pete Mill's blog" href="http://petemills.blogspot.ie/2011/08/halloween-spooky-eyes.html">Pete Mills blog</a> in which he created 'spooky' blinking eyes. I thought it would be nice to add motion to it so I decided to add a servo motor so that the eyes would turn and blink...

So ebay to the rescue, ping pong balls galore and Phenoptix supplied the LED's (10mm-green-prewired-led-12v).

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3732_small.jpg){:class="img-blog-post"}

Sean did a great job on the eyes..

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3734_small.jpg){:class="img-blog-post"}

When we assembled the eyes the LED's created a bright spot inside the ping pong balls. A piece of cotton wool worked nicely as a diffuser.

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3735_small.jpg){:class="img-blog-post"}

The LED's and Ping Pong balls were hot glued to the Ice Lolly sticks (Popsicle sticks).

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3760_small.jpg){:class="img-blog-post"}

I got some mini servos on ebay and I used a small attiny 2313 breadboard header (from <a title="Tinkerlog" href="http://tinkerlog.com/2009/01/18/attiny-breadboard-headers/">Tinkerlog</a>), from a previous project, to drive the servo and the LED's.

Note the LED's were driven by a small NPN transistor. We needed a waterproof project box and the box containing decking screws did the job just fine.

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3757_small.jpg){:class="img-blog-post"}

Ready to be tested..

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3762_small.jpg){:class="img-blog-post"}

I'll try to add a video of the eyes in action once I have figured out how to add video. They did look spooky and on Haloween night they were a great sucess with the 'trick or treaters'

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3800_small.jpg){:class="img-blog-post"}

Of course there were pumpkins as well!

![]({{ site.baseurl }}/assets/images/normal/2011/10/img_3803_small.jpg){:class="img-blog-post"}

Due to a hard drive crash I have no Schematics or Code, the board was a standard Atmel Attiny2313 setup with a NPN transistor driving the LED's and the servo was driven directly by the Attiny, some pwm code...
