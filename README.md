<h1>Adobe Business Catalyst Reset Project</h1>
=====================================

<p>This project aims to reset the default style sheet served for any Adobe Business Catalyst website.</p>
<p>The purpose of this is to reset all the pre-defined styles, fix incorrectly applied classes and methods and make minor changes to make it easier to apply consistent custom styles for your own site which won't conflict with 3rd party style sheets and javascript.</p>
<h2>How to use</h2>
<p>Just hot link the latest reset or normalised style sheet inside your html file as the first CSS reference.</p>
<p>For all the current release information please visit <a href="http://itbusiness.github.com/Adobe-Business-Catalyst-Reset-Project/" target="_blank">the Git Hub Page</a>.</p>
<!--
&lt;link href="/StyleSheets/ModuleStyleSheets.css" type="text/css" rel="StyleSheet" /&gt;
-->
<h2>A little background</h2>
<p>Whenever you create a new Adobe Business Catalyst website you'll notice the following line of code gets added to any HTML file you upload.
<pre>
&lt;link href="/StyleSheets/ModuleStyleSheets.css" type="text/css" rel="StyleSheet" /&gt;
</pre>
<p>This style sheet is the default style sheet served by Business Catalyst in order to pre-style a basic website.</p>
<p>A major issue with this is that the styles often conflict with your own custom stylesheet and many "default" styles do not relect what you may want to appear in your website.</p>
<p>There is also very little consistency in font-sizes, line-heights, margins, padding which make it very difficult to create a website which conforms to basic design principles and make a site look its best.</p>
<h2>Components</h2>
<p>There are two alternative components to this project:</p>
<ul>
<li>The Normalisation Sheet (which is now the current standard)</li>
<li>The Reset Sheet</li>
</ul>
<h3>The Normalisation Sheet</h3>
<p>One of the major elements of the normalisation sheet is to preserve useful browser defaults rather than erasing them.</p>
<p>This sheet is based on the work by <a href="http://nicolasgallagher.com/about-normalize-css/" rel="nofollow" target="_blank">Nicolas Gallagher</a> and <a href="http://sonspring.com/journal/formalize-css" target="_blank" rel="nofollow">Nathan Smith</a> who both have spent considerable time researching and testing cross-browser compliant styles.</p>
<p>The normalisation sheet is now the preferred method for the project however the Reset Sheet will be kept as an alternative resource.</p>
<h3>The Reset Sheet</h3>
<p>This is an alternative approach and resets all pre-defined styles to <a href="http://meyerweb.com/eric/tools/css/reset/" target="_blank">Eric Meyer's CSS Reset Sheet.</a></p>
<p>This tool is a widely used stylesheet to resolve many browser inconsistencies. This has been used as the basis for much of this project but other issues and inconsistencies specific to Business Catalyst have also been addressed.</p>
<h2>Current Fixes</h2>
<p>To Date the following items have been addressed:</p>
<ul>
<li>Resolved incorrect use of .clear method and applied correct use of .clearfix</li>
<li>Made all button styles consistent with use of image button in eCommerce template</li>
<li>Removed all default padding & margins.</li>
<li>Reset all typography font-sizes, line-heights, colors.</li>
<li>Allowed all inheritable elements to properly be styled from their parent objects.</li>
</ul>
<h2>Known Issues</h2>
<ul>
<li>Please refer to the GitHub Page for current release notes.</li>
</ul>
