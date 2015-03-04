# jquery.parallax-scroll
Smooth parallax effect on vertical page scrolling

<strong>Browser Support</strong>
Chrome 30+ (more browsers to come in further revisions)

<strong>How to use</strong>
Insert the script in your page, nothing more to do.
Add the attribute 'data-parallax' to the dom elements you want with a <a href="http://en.wikipedia.org/wiki/JSON#Data_types.2C_syntax_and_example">json syntax</a> that contains optionnals parameters and properties you want change.

<strong>Parameters</strong>
<em>from-scroll</em> : vertical scroll position the animation starts (default: when the element is visible)
<em>distance</em> : distance on vertical scroll position the animation will last (default: the window visible height)
<em>to-scroll</em> : vertical scroll position the animation ends (default: <em>from-scroll</em>+<em>to-scroll</em>)
<em>smoothness</em> : factor that slowdown the animation, the more the smoothier (default: 30)

<strong>Properties</strong>
<em>x</em> : x axe position (pixel)
<em>y</em> : y axe position (pixel)
<em>z</em> : z axe position (pixel)

<a href="http://free.matthieu.com/jquery.parallax-scroll/demo.html">Demo</a>