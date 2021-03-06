---
layout: default
permalink: 1.0/en/grid-system/positioning-layout
lang: en
title: Positioning Layout
description: 
---

<p class="girlik">
    Now you have more options to position. You can do things like "Left, origin, right, left top, top, top right, left bottom, bottom, bottom right and baseline". You can also define offsets and move away from one side.
  </p>

  <h3>Positioning: f, ft, t, th, h, bh, b, fb, g</h3>
  <p>
    The parameters f, ft, t, th, h, bh, b, fb, g are used to position the contents on either side. The meanings of the parameters are described more clearly below. The f, t, g, b, h on the keyboard are determined by the physical location of the letters.
  </p>

  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div style="height:300px;">
        <div data-gnl="1 /3 ft">ft: leFt Top</div>
        <div data-gnl="1 /3 t">t: Top</div>
        <div data-gnl="1 /3 th">th: Top rigHt</div>
        <div data-gnl="1 /3 f">f: leFt</div>
        <div data-gnl="1 /3 g">g: oriGin</div>
        <div data-gnl="1 /3 h">h: rigHt</div>
        <div data-gnl="1 /3 fb">fb: leFt Bottom</div>
        <div data-gnl="1 /3 b">b: Bottom</div>
        <div data-gnl="1 /3 bh">bh: Bottom rigHt</div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div style="height:300px;">
      <div data-gnl="1 /3 ft">ft: leFt Top</div>
      <div data-gnl="1 /3 t">t: Top</div>
      <div data-gnl="1 /3 th">th: Top rigHt</div>
      <div data-gnl="1 /3 f">f: leFt</div>
      <div data-gnl="1 /3 g">g: oriGin</div>
      <div data-gnl="1 /3 h">h: rigHt</div>
      <div data-gnl="1 /3 fb">fb: leFt Bottom</div>
      <div data-gnl="1 /3 b">b: Bottom</div>
      <div data-gnl="1 /3 bh">bh: Bottom rigHt</div>
    </div>
  {% endhighlight %}

  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div data-gnl="f">
        <div data-gnl="1 /3">f: leFt</div>
      </div>
      <div data-gnl="g">
        <div data-gnl="1 /3">g: oriGin</div>
      </div>
      <div data-gnl="h">
        <div data-gnl="1 /3">h: rigHt</div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div data-gnl="f">
      <div data-gnl="1 /3">f: leFt</div>
    </div>
    <div data-gnl="g">
      <div data-gnl="1 /3">g: oriGin</div>
    </div>
    <div data-gnl="h">
      <div data-gnl="1 /3">h: rigHt</div>
    </div>
  {% endhighlight %}
  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div data-gnl="1 /3 t" style="height:300px;">
        <div>t: Top</div>
      </div>
      <div data-gnl="1 /3 g" style="height:300px;">
        <div>g: oriGin</div>
      </div>
      <div data-gnl="1 /3 b" style="height:300px;">
        <div>b: Bottom</div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div data-gnl="1 /3 t" style="height:300px;">
      <div>t: Top</div>
    </div>
    <div data-gnl="1 /3 g" style="height:300px;">
      <div>g: oriGin</div>
    </div>
    <div data-gnl="1 /3 b" style="height:300px;">
      <div>b: Bottom</div>
    </div>
  {% endhighlight %}

  <h3>Positioning: _f, _ft, _t, _th, _h, _bh, _b, _fb, _g</h3>
  <p>
    _f, _ft, _t, _th, _h, _bh, _b, _fb, _g parameters are used to locate an item itself. The meanings of the parameters are described more clearly below. The f, t, g, b, h on the keyboard are determined by the physical location of the letters.
  </p>
  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div style="height:150px;">
        <div data-gnl="3 /10 _t">_t: Top itself</div>
        <div data-gnl="3 /10 _g">_g: oriGin itself</div>
        <div data-gnl="3 /10 _b">_b: Bottom itself</div>
      </div>
      <div style="height:150px;">
        <div data-gnl="3 /10 _l">_f: leFt itself</div>
        <div data-gnl="3 /10 _o">_g: oriGin itself</div>
        <div data-gnl="3 /10 _s">_h: rigHt itself</div>
      </div>
      <div style="height:150px;">
        <div data-gnl="3 /10 _lt">_ft: leFt Top itself</div>
        <div data-gnl="3 /10 _as">_bh: Bottom rigHt itself</div>
      </div>
      <div style="height:150px;">
        <div data-gnl="3 /10 _la">_fb: leFt Bottom itself</div>
        <div data-gnl="3 /10 _ts">_th: Top rigHt itself</div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div style="height:150px;">
      <div data-gnl="3 /10 _f">_f: Top itself</div>
      <div data-gnl="3 /10 _g">_g: oriGin itself</div>
      <div data-gnl="3 /10 _b">_b: Bottom itself</div>
    </div>
    <div style="height:150px;">
      <div data-gnl="3 /10 _l">_f: leFt itself</div>
      <div data-gnl="3 /10 _o">_g: oriGin itself</div>
      <div data-gnl="3 /10 _s">_h: rigHt itself</div>
    </div>
    <div style="height:150px;">
      <div data-gnl="3 /10 _lt">_ft: leFt Top itself</div>
      <div data-gnl="3 /10 _as">_bh: Bottom rigHt itself</div>
    </div>
    <div style="height:150px;">
      <div data-gnl="3 /10 _la">_fb: leFt Bottom itself</div>
      <div data-gnl="3 /10 _ts">_th: Top rigHt itself</div>
    </div>
  {% endhighlight %}

  <h3>Positioning: <span data-metin="dikkat">stretch | stretch-it</span></h3>
  <p>"stretch" value extends the item content along its length.</p>
  <p>"stretch-it" value extends according to the state of the item in the item.</p>
  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div data-gnl="1 /2 stretch" style="height:500px;">
        <div data-gnl="0">
          stretch
        </div>
        <div data-gnl="0">
          stretch
        </div>
        <div data-gnl="0">
          stretch
        </div>
      </div>
      <div data-gnl="1 /2" style="height:500px;">
        <div data-gnl="0 lt">
          lt: left-top
        </div>
        <div data-gnl="0">
          default (stretch)
        </div>
        <div data-gnl="0 lt">
          lt: left-top
        </div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div data-gnl="1 /2 stretch" style="height:500px;">
      <div data-gnl="0">
        stretch
      </div>
      <div data-gnl="0">
        stretch
      </div>
      <div data-gnl="0">
        stretch
      </div>
    </div>
    <div data-gnl="1 /2" style="height:500px;">
      <div data-gnl="0 lt">
        lt: left-top
      </div>
      <div data-gnl="0">
        default (stretch)
      </div>
      <div data-gnl="0 lt">
        lt: left-top
      </div>
    </div>
  {% endhighlight %}
  <p></p>

  <h3>Positioning: <span data-metin="dikkat">baseline | baseline-it</span></h3>
  <p>"baseline" value indicates an item content with the main line.</p>
  <p>"baseline-it" value indicates an item in the baseline position.</p>
  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div>
        <div data-gnl="0" style="font-size:2em">
          Default example text.
        </div>
        <div data-gnl="0">
          Default example text.
        </div>
      </div>
      <div data-gnl="baseline">
        <div data-gnl="0" style="font-size:2em">
          Example text "baseline".
        </div>
        <div data-gnl="0">
          Example text "baseline".
        </div>
      </div>
      <div>
        <div data-gnl="0 baseline-it" style="font-size:2em">
          Example text "baseline-it".
        </div>
        <div data-gnl="0 baseline-it">
          Example text "baseline-it".
        </div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div>
      <div data-gnl="0" style="font-size:2em">
        Default example text.
      </div>
      <div data-gnl="0">
        Default example text.
      </div>
    </div>
    <div data-gnl="baseline">
      <div data-gnl="0" style="font-size:2em">
        Example text "baseline".
      </div>
      <div data-gnl="0">
        Example text "baseline".
      </div>
    </div>
    <div>
      <div data-gnl="0 baseline-it" style="font-size:2em">
        Example text "baseline-it".
      </div>
      <div data-gnl="0 baseline-it">
        Example text "baseline-it".
      </div>
    </div>
  {% endhighlight %}
  <p></p>

  <h3>Positioning: <span data-metin="dikkat">wrap-reverse | row-reverse | col-reverse</span></h3>
  <p>"wrap-reverse" value indicates the item content in the reverse direction.</p>
  <p>"row-reverse" value indicates the row of an item in the reverse direction.</p>
  <p>"col-reverse" value indicates the column of an item content in the reverse direction.</p>

  <div class="örnek">
    <h3>Preview</h3>
    <div class="önizleme">
      <div data-gnl="wrap-reverse">
        <div data-gnl="1 /3">
          wrap-reverse #1
        </div>
        <div data-gnl="1 /3">
          wrap-reverse #2
        </div>
        <div data-gnl="1 /3">
          wrap-reverse #3
        </div>
        <div data-gnl="1 /3">
          wrap-reverse #4
        </div>
        <div data-gnl="1 /3">
          wrap-reverse #5
        </div>
        <div data-gnl="1 /3">
          wrap-reverse #6
        </div>
      </div>
      <div data-gnl="row-reverse">
        <div data-gnl="1 /3">
          row-reverse #1
        </div>
        <div data-gnl="1 /3">
          row-reverse #2
        </div>
        <div data-gnl="1 /3">
          row-reverse #3
        </div>
        <div data-gnl="1 /3">
          row-reverse #4
        </div>
        <div data-gnl="1 /3">
          row-reverse #5
        </div>
        <div data-gnl="1 /3">
          row-reverse #6
        </div>
      </div>
      <div data-gnl="col-reverse">
        <div data-gnl="1 /3">
          col-reverse #1
        </div>
        <div data-gnl="1 /3">
          col-reverse #2
        </div>
        <div data-gnl="1 /3">
          col-reverse #3
        </div>
      </div>
    </div>
  </div>
  {% highlight html %}
    <div data-gnl="wrap-reverse">
      <div data-gnl="1 /3">
        wrap-reverse #1
      </div>
      <div data-gnl="1 /3">
        wrap-reverse #2
      </div>
      <div data-gnl="1 /3">
        wrap-reverse #3
      </div>
      <div data-gnl="1 /3">
        wrap-reverse #4
      </div>
      <div data-gnl="1 /3">
        wrap-reverse #5
      </div>
      <div data-gnl="1 /3">
        wrap-reverse #6
      </div>
    </div>
    <div data-gnl="row-reverse">
      <div data-gnl="1 /3">
        row-reverse #1
      </div>
      <div data-gnl="1 /3">
        row-reverse #2
      </div>
      <div data-gnl="1 /3">
        row-reverse #3
      </div>
      <div data-gnl="1 /3">
        row-reverse #4
      </div>
      <div data-gnl="1 /3">
        row-reverse #5
      </div>
      <div data-gnl="1 /3">
        row-reverse #6
      </div>
    </div>
    <div data-gnl="col-reverse">
      <div data-gnl="1 /3">
        col-reverse #1
      </div>
      <div data-gnl="1 /3">
        col-reverse #2
      </div>
      <div data-gnl="1 /3">
        col-reverse #3
      </div>
    </div>
  {% endhighlight %}