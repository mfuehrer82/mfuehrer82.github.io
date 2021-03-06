<h1 id="material-design-lite">Material Design Lite</h1>

<h2 id="introduction">Introduction</h2>

<p><strong>Material Design Light (MDL)</strong> is a library of components for web developers based on Google's <strong>Material Design</strong> philosophy: "A visual language for our users that synthesizes the classic principles of good design with the innovation and possibility of technology and science." Understanding the goals and principles of Material Design is critical to the proper use of the MDL components. If you have not yet read the <a href="http://www.google.com/design/spec/material-design/introduction.html">Material Design Introduction</a>, you should do so before attempting to use the components.</p>

<p>The MDL components are created with CSS, JavaScript, and HTML. You can use the components to construct web pages and web apps that are attractive, consistent, and functional. Pages developed with MDL will adhere to modern web design principles like browser portability, device independence, and graceful degradation.</p>

<p>The MDL component library includes new versions of common user interface controls such as buttons, check boxes, and text fields, adapted to follow Material Design concepts. The library also includes enhanced and specialized features like cards, column layouts, sliders, spinners, tabs, typography, and more.</p>

<p>MDL is free to download and use, and may be used with or without any build library or development environment (such as <a href="http://www.getmdl.io/">Material Design Lite</a>). It is a cross-browser, cross-OS web developer's toolkit that can be used by anyone who wants to write more productive, portable, and &mdash; most importantly &mdash; usable web pages.</p>

<h2 id="getting-started">Getting started</h2>

<h3 id="get-the-components">Get the components</h3>

<p>To obtain the components, clone or download the <a href="https://github.com/google/material-design-lite">GitHub MDL repository</a>. Copy the entire package (the top-level folder and everything below it) to the project folder where you will write your HTML pages. This ensures that your project can access all of MDL's components and assets, and that you always have the original files for reference in case you break something. :-)</p>

<h3 id="include-the-master-css-and-javascript">Include the master CSS and JavaScript</h3>

<p>In each HTML page in your project, include the minified (compressed) CSS and JavaScript files using standard relative-path references and the Material Icon font. This example assumes that a copy of the MDL package folders resides in your project folder.</p>

<pre><code class="html">&lt;link rel="stylesheet" href="css/material.min.css"&gt;
&lt;script src="js/material.min.js"&gt;&lt;/script&gt;
&lt;link rel="stylesheet" href="//fonts.googleapis.com/icon?family=Material+Icons"&gt;
</code></pre>

<p>That's it! You are now ready to use the MDL components.</p>

<h3 id="use-the-components">Use the components</h3>

<p>In general, follow these basic steps to use an MDL component in your HTML page.</p>

<ol>
<li>Start with a standard HTML element, such as <code>&lt;button&gt;</code>, <code>&lt;div&gt;</code>, or <code>&lt;ul&gt;</code>, depending on the MDL component you want to use. This establishes the element in the page and readies it for MDL modification.<br><br></li>
<li>Add one or more MDL-specific CSS classes to the element, such as <code>mdl-button</code> or   <code>mdl-tabs__panel</code> again depending on the component. The classes apply the MDL enhancements to the element and effectively turn it into an MDL component.<br><br></li>
<li>View the page, preferably in multiple browsers on multiple devices, to ensure that the component looks and behaves as expected.</li>
</ol>

<blockquote>
  <p><strong>A note about HTML elements and MDL CSS classes</strong>
  Material Design Lite uses CSS <em>independent classes</em>, which can apply to any HTML element, to construct components. For some components, you can use almost any element. For other components, some elements give better visual or behavioral performance than others. The examples in each component's README file use elements that perform well as that component. If you must use elements other than those shown in the examples, we encourage you to experiment to find the best combination of HTML elements and MDL CSS classes for your application.</p>
</blockquote>

<h2 id="what%27s-next%3F">What's next?</h2>

<p>Detailed instructions for using the components, including MDL classes and their effects, coding considerations, and configuration options, can be found in each component's <code>README.md</code> file. Working examples using various options are in each component's <code>demo.html</code> page.</p>

<h2 id="license">License</h2>

<p>Copyright Google, 2015. Licensed under an Apache-2 license.</p>
