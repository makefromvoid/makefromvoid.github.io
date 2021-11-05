---
title: The Halloween Matrix
description: Halloween Fun
category: Electronics
categories:
- avr
- electronics
- halloween
image: /assets/images/normal/2013/10/2013-10-25 08.35.12_small.jpg
image-caption: test image caption
type: post # used in _layouts/posts.html:section
# Note: layout type of files in '_posts' is configured as 'post' in _config.yml
---
Halloween is nearing and again I'm looking for a project for the boy and girl. In the past I have used the attiny breakout board from tinkerlog and browsing Alex's site one of the projects I liked was a 64 pixel animated LED Matrix. Here is the link to the <a href="http://tinkerlog.com/howto/64pixels/">original article</a>.

I thought it would be nice to have the boy and girl draw the animations themselves on a 8 by 8 grid and maybe even have them decode the images from binary to decimal format.... I think children over the age of '10' should be able to count in binary ;- )

Here is the Tess drawing one 'frame'

![]({{ site.baseurl }}/assets/images/normal/2013/10/2013-10-20 12.13.55_small.jpg){:class="img-blog-post"}

And a close up, no fear here ;-) For each row they had to add the individual bits to calculate the 'row' value. The image below shows the 2 frames making up a bunny which blinks and flops one ear.

![]({{ site.baseurl }}/assets/images/normal/2013/10/2013-10-20 12.23.43_small.jpg){:class="img-blog-post"}

I pretty much followed Alex's instructions, I had to put a zener in to drop a volt, the LED's were a little bit to bright.
Here is the circuit on a breadboard, note I use Alex's <a href="http://tinkerlog.com/howto/tiny2313-header/">ATtiny2313</a> header, the LED Matrix is a <a href="http://www.futurlec.com/LED/LEDM88G.shtml">LEDM88G</a> from Futurlec.

![]({{ site.baseurl }}/assets/images/normal/2013/10/2013-10-20 11.53.03_small.jpg){:class="img-blog-post"}

Now it was time to purchase 2 sets of parts i.e. 2 times:
- ATtiny2313-20P
- LED Matrix
- Zener Diode
- Battery Holder

![]({{ site.baseurl }}/assets/images/normal/2013/10/2013-10-20 11.53.03_small.jpg){:class="img-blog-post"}


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

