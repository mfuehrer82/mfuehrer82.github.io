<h2 id="introduction">Introduction</h2>

<p>The Material Design Lite (MDL) <strong>tooltip</strong> component is an enhanced version of the standard HTML tooltip as produced by the <code>title</code> attribute. A tooltip consists of text and/or an image that clearly communicates additional information about an element when the user hovers over or, in a touch-based UI, touches the element. The MDL tooltip component is pre-styled (colors, fonts, and other settings are contained in <em>material.min.css</em>) to provide a vivid, attractive visual element that displays related but typically non-essential content, e.g., a definition, clarification, or brief instruction.</p>

<p>Tooltips are a ubiquitous feature of most user interfaces, regardless of a site's content or function. Their design and use is an important factor in the overall user experience. See the tooltip component's <a href="http://www.google.com/design/spec/components/tooltips.html">Material Design specifications page</a> for details.</p>

<h3 id="to-include-an-mdl-%2A%2Atooltip%2A%2A-component%3A">To include an MDL <strong>tooltip</strong> component:</h3>

<p>&nbsp;1. Code an element, such as a <code>&lt;div&gt;</code>, <code>&lt;p&gt;</code>, or <code>&lt;span&gt;</code>, and style it as desired; this will be the tooltip's target. Include an <code>id</code> attribute and unique value to link the container to its tooltip.</p>

<pre><code class="html">&lt;p id="tt1"&gt;HTML&lt;/p&gt;
</code></pre>

<p>&nbsp;2. Following the target element, code a second element, such as a <code>&lt;div&gt;</code>, <code>&lt;p&gt;</code>, or <code>&lt;span&gt;</code>; this will be the tooltip itself. Include a <code>for</code> (or <code>data-mdl-for</code>) attribute whose value matches that of the target's <code>id</code>.</p>

<pre><code class="html">&lt;p id="tt1"&gt;HTML&lt;/p&gt;
&lt;span for="tt1"&gt;HyperText Markup Language&lt;/span&gt;
</code></pre>

<p>&nbsp;3. Add one or more MDL classes, separated by spaces, to the tooltip element using the <code>class</code> attribute.</p>

<pre><code class="html">&lt;p id="tt1"&gt;HTML&lt;/p&gt;
&lt;span for="tt1" class="mdl-tooltip"&gt;HyperText Markup Language&lt;/span&gt;
</code></pre>

<p>The tooltip component is ready for use.</p>

<h4 id="examples">Examples</h4>

<p>A target with a simple text tooltip.</p>

<pre><code class="html">&lt;p&gt;HTML is related to but different from &lt;span id="xml"&gt;&lt;i&gt;XML&lt;/i&gt;&lt;/span&gt;.&lt;/p&gt;
&lt;span class="mdl-tooltip" for="xml"&gt;eXtensible Markup Language&lt;/span&gt;
</code></pre>

<p>A target with "rich" (containing HTML markup) tooltip text.</p>

<pre><code class="html">&lt;p&gt;HTML is related to but different from &lt;span id="xml"&gt;&lt;i&gt;XML&lt;/i&gt;&lt;/span&gt;.&lt;/p&gt;
&lt;span class="mdl-tooltip" for="xml"&gt;e&lt;b&gt;X&lt;/b&gt;tensible &lt;b&gt;M&lt;/b&gt;arkup &lt;b&gt;L&lt;/b&gt;anguage&lt;/span&gt;
</code></pre>

<p>A target with a long text tooltip that automatically wraps.</p>

<pre><code class="html">&lt;p&gt;HTML is related to but different from &lt;span id="xml"&gt;&lt;i&gt;XML&lt;/i&gt;&lt;/span&gt;.&lt;/p&gt;
&lt;span class="mdl-tooltip" for="xml"&gt;XML is an acronym for eXtensible Markup Language&lt;/span&gt;
</code></pre>

<p>A target with tooltip text in a larger font size.</p>

<pre><code class="html">&lt;p&gt;HTML is related to but different from &lt;span id="xml"&gt;&lt;i&gt;XML&lt;/i&gt;&lt;/span&gt;.&lt;/p&gt;
&lt;span class="mdl-tooltip mdl-tooltip--large" for="xml"&gt;eXtensible Markup Language&lt;/span&gt;
</code></pre>

<p>A target with a tooltip containing both an image and text.</p>

<pre><code class="html">&lt;p&gt;HTML is related to but different from &lt;span id="xml"&gt;&lt;i&gt;XML&lt;/i&gt;&lt;/span&gt;.&lt;/p&gt;
&lt;span class="mdl-tooltip" for="xml"&gt;
&lt;img src="xml-logo-small.png" width="20" height="10"&gt; eXtensible Markup Language&lt;/span&gt;
</code></pre>

<h2 id="configuration-options">Configuration options</h2>

<p>The MDL CSS classes apply various predefined visual enhancements to the tooltip. The table below lists the available classes and their effects.</p>

<table>
<thead>
<tr>
  <th>MDL class</th>
  <th>Effect</th>
  <th>Remarks</th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>mdl-tooltip</code></td>
  <td>Defines a container as an MDL tooltip</td>
  <td>Required on tooltip container element</td>
</tr>
<tr>
  <td><code>mdl-tooltip--large</code></td>
  <td>Applies large-font effect</td>
  <td>Optional; goes on tooltip container element</td>
</tr>
<tr>
  <td><code>mdl-tooltip--left</code></td>
  <td>Positions the tooltip to the left of the target</td>
  <td>Optional; goes on tooltip container element</td>
</tr>
<tr>
  <td><code>mdl-tooltip--right</code></td>
  <td>Positions the tooltip to the right of the target</td>
  <td>Optional; goes on tooltip container element</td>
</tr>
<tr>
  <td><code>mdl-tooltip--top</code></td>
  <td>Positions the tooltip to the top of the target</td>
  <td>Optional; goes on tooltip container element</td>
</tr>
<tr>
  <td><code>mdl-tooltip--bottom</code></td>
  <td>Positions the tooltip to the bottom of the target</td>
  <td>Optional; goes on tooltip container element</td>
</tr>
</tbody>
</table>