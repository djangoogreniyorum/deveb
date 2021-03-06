---
layout: default
permalink: 1.0/en/grid-system/formating-layout
lang: en
title: Formating Layout
description: 
---

<p class="girlik">
  By default, you improve your designs in some types. When you arrive, you will use different types. The types of shapes found in this section will make your work easier.
</p>
<h2>Full Screen</h2>
<p>
  If you want to make your designs in fullscreen layout, you will use the "fullscreen" parameter prepared by <span class="simget">deveb</span>. You can use the HTML body tag to specify the screen range you want.
</p>

<div class="örnek">
  <h3>Preview</h3>
  <a href="#">If you want to demo, click here.</a> <br><br>
  {% highlight html %}
  <body data-gnl="fullscreen">
    Everything in this area remains in full-screen layout.
  </body>
  {% endhighlight %}
</div>
<h2>Container</h2>
<p>
  Use static widths according to the screens when making your designs. You only need to use the "container" parameter for this.
</p>
<div class="örnek">
  <h3>Example</h3>
  <div class="önizleme">
    <div data-gnl="container">
      <div data-gnl="1 /3">
        1 /3
      </div>
      <div data-gnl="1 /3">
        1 /3
      </div>
      <div data-gnl="1 /3">
        1 /3
      </div>
    </div>
  </div>
  {% highlight html %}
  <div data-gnl="container">
    <div data-gnl="1 /3">
      1 /3
    </div>
    <div data-gnl="1 /3">
      1 /3
    </div>
    <div data-gnl="1 /3">
      1 /3
    </div>
  </div>
  {% endhighlight %}
</div>

<h2>Fit</h2>
<p>
  You may have designs that you want to fit where you have a transversal area. Then you only need to use the "fit" parameter. In some cases you may need to use it with the "column" parameter. Examine the examples to better understand them.
</p>

<div class="örnek">
  <h3>Example</h3>
  <a href="#">If you want to demo, click here.</a> <br><br>
  {% highlight html %}
  <body data-gnl="fullscreen">
    <div data-gnl="fit">
      This area is fit to full screen.
    </div>
  </body>
  {% endhighlight %}
</div>

<h2>0 (zero)</h2>
<p>
  You may want to use the width according to the content when making your designs. You only need to use the "0" parameter for this.
</p>
<div class="örnek">
  <h3>Example</h3>
  <div class="önizleme">
    <div data-gnl="0">
      0
    </div>
    <div data-gnl="1 /3">
      1 /3
    </div>
    <div data-gnl="1 /3">
      1 /3
    </div>
  </div>
</div>  
{% highlight html %}
  <div data-gnl="0">
    0
  </div>
  <div data-gnl="1 /3">
    1 /3
  </div>
  <div data-gnl="1 /3">
    1 /3
  </div>
{% endhighlight %}


<h3>no-overflow & no-wrap</h3>
  <p>"no-overflow" prevents content from overflowing.</p>
  <p>"no-wrap" prevents the content from being moved to the bottom line and displays it on one line.</p>
  
  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div data-gnl="1 /24 no-overflow">
        Are you the one we can not write over?
      </div>
      <div data-gnl="no-wrap">
        <div>
          These contents are displayed under no-wrap effect.
        </div>
        <div>
          These contents are displayed under no-wrap effect.
        </div>
        <div>
          These contents are displayed under no-wrap effect.
        </div>
        <div>
          These contents are displayed under no-wrap effect.
        </div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div data-gnl="1 /24 no-overflow">
      Are you the one we can not write over?
    </div>
    <div data-gnl="no-wrap">
      <div>
        These contents are displayed under no-wrap effect.
      </div>
      <div>
        These contents are displayed under no-wrap effect.
      </div>
      <div>
        These contents are displayed under no-wrap effect.
      </div>
      <div>
        These contents are displayed under no-wrap effect.
      </div>
    </div>
  {% endhighlight %}