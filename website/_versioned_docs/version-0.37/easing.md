---
id: version-0.37-easing
original_id: easing
title: easing
---
<a id="content"></a><h1><a class="anchor" name="easing"></a>Easing <a class="hash-link" href="docs/easing.html#easing">#</a></h1><div><div><p>This class implements common easing functions. The math is pretty obscure,
but this cool website has nice visual illustrations of what they represent:
<a href="http://xaedes.de/dev/transitions/">http://xaedes.de/dev/transitions/</a></p></div><span><h3><a class="anchor" name="methods"></a>Methods <a class="hash-link" href="docs/easing.html#methods">#</a></h3><div class="props"><div class="prop"><h4 class="methodTitle"><a class="anchor" name="step0"></a><span class="methodType">static </span>step0<span class="methodType">(n)</span> <a class="hash-link" href="docs/easing.html#step0">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="step1"></a><span class="methodType">static </span>step1<span class="methodType">(n)</span> <a class="hash-link" href="docs/easing.html#step1">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="linear"></a><span class="methodType">static </span>linear<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#linear">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="ease"></a><span class="methodType">static </span>ease<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#ease">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="quad"></a><span class="methodType">static </span>quad<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#quad">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="cubic"></a><span class="methodType">static </span>cubic<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#cubic">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="poly"></a><span class="methodType">static </span>poly<span class="methodType">(n)</span> <a class="hash-link" href="docs/easing.html#poly">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="sin"></a><span class="methodType">static </span>sin<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#sin">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="circle"></a><span class="methodType">static </span>circle<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#circle">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="exp"></a><span class="methodType">static </span>exp<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#exp">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="elastic"></a><span class="methodType">static </span>elastic<span class="methodType">(bounciness)</span> <a class="hash-link" href="docs/easing.html#elastic">#</a></h4><div><p>A simple elastic interaction, similar to a spring.  Default bounciness
is 1, which overshoots a little bit once.  0 bounciness doesn't overshoot
at all, and bounciness of N &gt; 1 will overshoot about N times.</p><p>Wolfram Plots:</p><p>  <a href="http://tiny.cc/elastic_b_1">http://tiny.cc/elastic_b_1</a> (default bounciness = 1)
  <a href="http://tiny.cc/elastic_b_3">http://tiny.cc/elastic_b_3</a> (bounciness = 3)</p></div></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="back"></a><span class="methodType">static </span>back<span class="methodType">(s)</span> <a class="hash-link" href="docs/easing.html#back">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="bounce"></a><span class="methodType">static </span>bounce<span class="methodType">(t)</span> <a class="hash-link" href="docs/easing.html#bounce">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="bezier"></a><span class="methodType">static </span>bezier<span class="methodType">(x1, y1, x2, y2)</span> <a class="hash-link" href="docs/easing.html#bezier">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="in"></a><span class="methodType">static </span>in<span class="methodType">(easing)</span> <a class="hash-link" href="docs/easing.html#in">#</a></h4></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="out"></a><span class="methodType">static </span>out<span class="methodType">(easing)</span> <a class="hash-link" href="docs/easing.html#out">#</a></h4><div><p>Runs an easing function backwards.</p></div></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="inout"></a><span class="methodType">static </span>inOut<span class="methodType">(easing)</span> <a class="hash-link" href="docs/easing.html#inout">#</a></h4><div><p>Makes any easing function symmetrical.</p></div></div></div></span></div><p class="edit-page-block">You can <a target="_blank" href="https://github.com/facebook/react-native/blob/master/Libraries/Animated/src/Easing.js">edit the content above on GitHub</a> and send us a pull request!</p><div class="docs-prevnext"><a class="docs-prev" href="docs/dimensions.html#content">← Prev</a><a class="docs-next" href="docs/geolocation.html#content">Next →</a></div>