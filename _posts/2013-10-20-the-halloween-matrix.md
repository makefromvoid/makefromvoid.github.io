---
title: The Halloween Matrix
description: Halloween Fun
category: Electronics
categories:
- avr
- electronics
- halloween
featured-img: normal/2013/10/2013-10-25 08.35.12
image-caption: test image caption
type: post # used in _layouts/posts.html:section
# Note: layout type of files in '_posts' is configured as 'post' in _config.yml
---
Halloween is nearing and again I'm looking for a project for the boy and girl. In the past I have used the attiny breakout board from tinkerlog and browsing Alex's site one of the projects I liked was a 64 pixel animated LED Matrix. Here is the link to the 
{% include link.html link="http://tinkerlog.com/howto/64pixels/" link_text="original article" %}
.

I thought it would be nice to have the boy and girl draw the animations themselves on a 8 by 8 grid and maybe even have them decode the images from binary to decimal format.... I think children over the age of '10' should be able to count in binary ;- )

Here is the Tess drawing one 'frame'

{% include image.html src="/assets/images/normal/2013/10/2013-10-20 12.13.55.jpg" %}

And a close up, no fear here ;-) For each row they had to add the individual bits to calculate the 'row' value. The image below shows the 2 frames making up a bunny which blinks and flops one ear.

{% include image.html src="/assets/images/normal/2013/10/2013-10-20 12.23.43.jpg" %}

I pretty much followed Alex's instructions, I had to put a zener in to drop a volt, the LED's were a little bit to bright.
Here is the circuit on a breadboard, note I use Alex's {% include link.html link="http://tinkerlog.com/howto/tiny2313-header/" link_text="ATtiny2313" %} header, the LED Matrix is a {% include link.html link="http://www.futurlec.com/LED/LEDM88G.shtml" link_text="LEDM88G" %} from Futurlec.

{% include image.html src="/assets/images/normal/2013/10/2013-10-20 11.53.03.jpg" %}

Now it was time to purchase 2 sets of parts i.e. 2 times:
- ATtiny2313-20P
- LED Matrix
- Zener Diode
- Battery Holder

{% include image.html src="/assets/images/normal/2013/10/2013-10-23 21.05.30.jpg" %}


Sean's Animation 
<video width="300" height="200" muted loop autoplay>
    <source src="{{ site.baseurl }}/assets/video/normal/2013/10/MVI_3557.mp4" type="video/mp4"/>
    <source src="{{ site.baseurl }}/assets/video/normal/2013/10/MVI_3557.webm" type="video/webm"/> 
    Your Video does not support the video tag.
</video>
<br>
Tess's Animation
<video width="300" height="200" muted loop autoplay>
    <source src="{{ site.baseurl }}/assets/video/normal/2013/10/MVI_3558.mp4" type="video/mp4"/>
    <source src="{{ site.baseurl }}/assets/video/normal/2013/10/MVI_3558.webm" type="video/webm"/> 
    Your Video does not support the video tag.
</video>

Here are the boy and girl showing off the finished articles.

{% include image.html src="/assets/images/normal/2013/10/2013-10-25 08.35.12.jpg" %}
