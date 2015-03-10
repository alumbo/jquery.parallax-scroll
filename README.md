# jquery.parallax-scroll
Smooth parallax animations on vertical page scrolling using requestAnimationFrame and CSS3 3D transitions.

<h2>Browser Support</h2>
Chrome 30+, Firefox 34+, Safari 7.1+, IE 10+

<h2>How to use</h2>
Insert the script <em>jquery.parallax-scroll.js</em> in your page after jQuery, there is no more javascript code needed.<br/>
Add the attribute 'data-parallax' to the dom elements you want with a <a href="http://en.wikipedia.org/wiki/JSON#Data_types.2C_syntax_and_example" target="_blank">json syntax</a> that contains optionnals parameters and properties you want animate.

<h2>Parameters</h2>
<ul>
	<li><em>from-scroll</em>: vertical scroll position the animation starts (default: when the element is visible)</li>
	<li><em>distance</em>: distance on vertical scroll position the animation will last (default: the window visible height)</li>
	<li><em>to-scroll</em>: vertical scroll position the animation ends (default: <em>from-scroll</em> + <em>distance</em>)</li>
	<li><em>smoothness</em>: factor that slowdown the animation, the more the smoothier (default: 30)</li>
	<li><em>perspective</em>: 3d perspective applied on parent element in case of z axe use (default: 800)</li>
	<li><em>easing</em>: <a href="http://gsgd.co.uk/sandbox/jquery/easing/" target="_blank">Easing function</a> used to animate (note that the duration parameter is needed, <em>distance</em> and <em>to-scroll</em> will be ignored) - <a href="http://gsgd.co.uk/sandbox/jquery/easing/jquery.easing.1.3.js" target="_blank">jquery.easing.1.3.js</a> is required to use the optionnal feature.</li>
	<li><em>duration</em>: Duration of the easing animation, will be ignore if there is no easing paramater specified (frames)
</ul>

<h2>Properties</h2>
<ul>
	<li><em>x</em>: X axis translation (pixels)</li>
	<li><em>y</em>: Y axis translation (pixels)</li>
	<li><em>z</em>: Z axis translation (pixels)</li>
	<li><em>rotateX</em>: X axis rotation (degrees)</li>
	<li><em>rotateY</em>: Y axis rotation (degrees)</li>
	<li><em>rotateZ</em>: Z axis rotation (degrees)</li>
</ul>

<h2>Examples</h2>
<p>
	Move down the image by 230 pixels while vertical scrolling from when it shows up on screen bottom to when it disappears on screen top:<br/>
	<code>&lt;img src="img/paris.jpg" alt="Paris" data-parallax='{"y" : 230}'/&gt;</code>
</p>
<p>
	Translation to the right by 750 pixels with a lower smoothness effect when vertical scroll position is over 50 pixels:<br/>
	<code>&lt;li data-parallax='{"x": 750, "from-scroll": 50, "distance": 0, "smoothness": 10}'&gt;1&lt;/li&gt;</code>
</p>
<p>
	Rotation by 1000 degrees along the X axis from when the exclamation point shows up to the window height distance scroll position:<br/>
	<code>&lt;p data-parallax='{"rotateX":1000}'&gt;!&lt;/p&gt;</code>
</p>

<h3><a href="http://free.matthieu.com/jquery.parallax-scroll/demo.html" target="_blank">Demo</a></h3>
<p><a href="http://free.matthieu.com/jquery.parallax-scroll/stars.html" target="_blank">Bonus test with 100 stars</a></p>