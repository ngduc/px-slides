# Px-Slides

A simple slideshow element built with [Polymer.js](http://www.polymer-project.org/).

### Install

`
$ bower install px-slides --save
`

### Demo

You can see it in action [https://ipim.com](https://ipim.com)

http://component.kitchen/components/ngduc/px-slides

### Usage

Include the element like below:

	<script src="webcomponents.min.js"></script>
	<script src="polymer.min.js"></script>

	<link rel="import" href="px-slides.html">

Use the tag on your page:

	<px-slides>
		<img src="foo.jpg"/>
		<img src="bar.jpg"/>
	</px-slides>

You can also set "lazy-src" for images to load them on demand: (to reduce page loading time)

	<px-slides>
		<img lazy-src="foo.jpg"/>
		<img lazy-src="bar.jpg"/>
		<img lazy-src="baz.jpg"/>
	</px-slides>

Optional attributes for \<px-slides\> tag:
	
	width      // sets the width
	height     // sets the height
	auto       // whether to trigger the slideshow, default: false
	timer      // interval at which to perform the slideshow, default: 3s
	lazyTimer  // delay for lazy loading images (must be less than 'timer'), default: 1s
	


License
-------

[MIT License](http://www.opensource.org/licenses/mit-license.php)

&copy; 2013 Kaizhi Wei &lt;hello@kaizhiwei.com&gt;

&copy; 2015 Duc Nguyen &lt;ducjava@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
