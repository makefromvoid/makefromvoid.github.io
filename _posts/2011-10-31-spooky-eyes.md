---
title: Spooky eyes
description: Halloween Fun
category: Electronics
categories:
- avr
- electronics
- halloween
featured-img: normal/2011/10/img_3800
image-caption: test image caption
type: post # used in _layouts/posts.html:section
# Note: layout type of files in '_posts' is configured as 'post' in _config.yml
---
With Halloween approaching it was time to look for a little project. I came across <a title="Pete Mill's blog" href="http://petemills.blogspot.ie/2011/08/halloween-spooky-eyes.html">Pete Mills blog</a> in which he created 'spooky' blinking eyes. I thought it would be nice to add motion to it so I decided to add a servo motor so that the eyes would turn and blink...

So ebay to the rescue, ping pong balls galore and Phenoptix supplied the LED's (10mm-green-prewired-led-12v).

{% include image.html src="/assets/images/normal/2011/10/img_3732.jpg" %}

Sean did a great job on the eyes..

{% include image.html src="/assets/images/normal/2011/10/img_3734.jpg" %}

When we assembled the eyes the LED's created a bright spot inside the ping pong balls. A piece of cotton wool worked nicely as a diffuser.

{% include image.html src="/assets/images/normal/2011/10/img_3735.jpg" %}

The LED's and Ping Pong balls were hot glued to the Ice Lolly sticks (Popsicle sticks).

{% include image.html src="/assets/images/normal/2011/10/img_3760.jpg" %}

I got some mini servos on ebay and I used a small attiny 2313 breadboard header (from <a title="Tinkerlog" href="http://tinkerlog.com/2009/01/18/attiny-breadboard-headers/">Tinkerlog</a>), from a previous project, to drive the servo and the LED's.

Note the LED's were driven by a small NPN transistor. We needed a waterproof project box and the box containing decking screws did the job just fine.

{% include image.html src="/assets/images/normal/2011/10/img_3757.jpg" %}

Ready to be tested..

{% include image.html src="/assets/images/normal/2011/10/img_3762.jpg" %}

Below is a video of the eyes in action, they did look very spooky out in the garden on Haloween night and were a great sucess with the 'trick or treaters'

<video width="300" height="200" poster="{{ site.baseurl }}/assets/images/normal/2011/10/img_3800_small.jpg" muted loop autoplay>
    <source src="{{ site.baseurl }}/assets/video/normal/2011/10/MVI_3552.mp4" type="video/mp4"/>
    <source src="{{ site.baseurl }}/assets/video/normal/2011/10/MVI_3552.webm" type="video/webm"/> 
    Your Video does not support the video tag.
</video>
<br>
Of course there were pumpkins as well!

{% include image.html src="/assets/images/normal/2011/10/img_3803.jpg" %}

Due to a hard drive crash I have no Schematics or Code, the board was a standard Atmel Attiny2313 setup with a NPN transistor driving the LED's and the servo was driven directly by the Attiny, some pwm code...
