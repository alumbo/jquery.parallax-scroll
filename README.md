# jquery.parallax-scroll
Smooth parallax effect on vertical page scrolling

<h2>Browser Support</h2>
Chrome 30+ (more browsers to come in further revisions)

<h2>How to use</h2>
Insert the script in your page, nothing more to do.<br/>
Add the attribute 'data-parallax' to the dom elements you want with a <a href="http://en.wikipedia.org/wiki/JSON#Data_types.2C_syntax_and_example">json syntax</a> that contains optionnals parameters and properties you want change.

<h2>Parameters</h2>
<ul>
	<li><em>from-scroll</em> : vertical scroll position the animation starts (default: when the element is visible)</li>
	<li><em>distance</em> : distance on vertical scroll position the animation will last (default: the window visible height)</li>
	<li><em>to-scroll</em> : vertical scroll position the animation ends (default: <em>from-scroll</em>+<em>to-scroll</em>)</li>
	<li><em>smoothness</em> : factor that slowdown the animation, the more the smoothier (default: 30)</li>
</ul>

<h2>Properties</h2>
<ul>
	<li><em>x</em> : x axe position (pixel)</li>
	<li><em>y</em> : y axe position (pixel)</li>
	<li><em>z</em> : z axe position (pixel)</li>
</ul>

<a href="http://free.matthieu.com/jquery.parallax-scroll/demo.html">Demo</a>