# jquery.parallax-scroll
Smooth parallax animations on vertical page scrolling using requestAnimationFrame and CSS3 3D transitions.

<h2>Browser Support</h2>
Chrome 30+, Firefox 34+, Safari 7.1+, IE 10+

<h2>How to use</h2>
Insert the script <em>jquery.parallax-scroll.js</em> in your page after jQuery, there is no more javascript code needed.<br/>
Add the attribute 'data-parallax' to the dom elements you want with a <a href="http://en.wikipedia.org/wiki/JSON#Data_types.2C_syntax_and_example" target="_blank">json syntax</a> that contains optionnals parameters and properties you want animate.

<h2>Parameters</h2>
<ul>
	<li><em>from-scroll</em> : vertical scroll position the animation starts (default: when the element is visible)</li>
	<li><em>distance</em> : distance on vertical scroll position the animation will last (default: the window visible height)</li>
	<li><em>to-scroll</em> : vertical scroll position the animation ends (default: <em>from-scroll</em> + <em>distance</em>)</li>
	<li><em>smoothness</em> : factor that slowdown the animation, the more the smoothier (default: 30)</li>
	<li><em>perspective</em> : 3d perspective applied on parent element in case of z axe use (default: 800)</li>
</ul>

<h2>Properties</h2>
<ul>
	<li><em>x</em> : X axis translation (pixels)</li>
	<li><em>y</em> : Y axis translation (pixels)</li>
	<li><em>z</em> : Z axis translation (pixels)</li>
	<li><em>rotateX</em> : X axis rotation (degrees)</li>
	<li><em>rotateY</em> : Y axis rotation (degrees)</li>
	<li><em>rotateZ</em> : Z axis rotation (degrees)</li>
</ul>

<h2>Examples</h2>
<code>&lt;img src="img/paris.jpg" alt="Paris" data-parallax='{"y":230}'/&gt;</code><br/>
<code>&lt;li data-parallax='{"x":750,"from-scroll":50,"distance":0,"smoothness":10}'&gt;1&lt;/li&gt;</code><br/>
<code>&lt;p data-parallax='{"rotateX":1000}'&gt;!&lt;/p&gt;</code>

<h3><a href="http://free.matthieu.com/jquery.parallax-scroll/demo.html" target="_blank">Demo</a></h3>
<p><a href="http://free.matthieu.com/jquery.parallax-scroll/stars.html" target="_blank">Bonus test with 100 stars</a></p>