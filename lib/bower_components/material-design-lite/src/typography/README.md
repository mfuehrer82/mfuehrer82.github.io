<h2 id="introduction">Introduction</h2>

<p>The Material Design Lite (MDL) <strong>typography</strong> component is a comprehensive approach to standardizing the use of typefaces in applications and page displays. MDL typography elements are intended to replace the myriad fonts used by developers (which vary significantly in appearance) and provide a robust, uniform library of text styles from which developers can choose.</p>

<p>The "Roboto" typeface is the standard for MDL display; it can easily be integrated into a web page using the CSS3 <code>@font-face</code> rule. However, Roboto is most simply accessed and included using a single standard HTML <code>&lt;link&gt;</code> element, which can be obtained at <a href="http://www.google.com/fonts#UsePlace:use/Collection:Roboto">this Google fonts page</a>.</p>

<p>Because of the many possible variations in font display characteristics in HTML and CSS, MDL typography aims to provide simple and intuitive styles that use the Roboto font and produce visually attractive and internally consistent text results. See the typography component's <a href="http://www.google.com/design/spec/style/typography.html">Material Design specifications page</a> for details.</p>

<h2 id="basic-use">Basic use</h2>

<p>Include a link to the Google stylesheet that accesses the font and its desired variations.</p>

<pre><code class="html">&lt;head&gt;
&lt;link
 href='http://fonts.googleapis.com/css?family=Roboto:400,400italic,500,500italic,700,700italic'
 rel='stylesheet' type='text/css'&gt;
...
&lt;/head&gt;
</code></pre>

<h3 id="to-include-an-mdl-%2A%2Atypography%2A%2A-component%3A">To include an MDL <strong>typography</strong> component:</h3>

<p>&nbsp;1. Code any element (<code>&lt;div&gt;</code>,<code>&lt;p&gt;</code>,<code>&lt;span&gt;</code>, etc.) that can contain text, including whatever content is appropriate.</p>

<pre><code class="html">&lt;p&gt;This is a standard paragraph.&lt;/p&gt;
</code></pre>

<p>&nbsp;2. Add one or more MDL classes, separated by spaces, to the element using the <code>class</code> attribute.</p>

<pre><code class="html">&lt;p class="mdl-typography--body-1"&gt;This is a standard paragraph.&lt;/p&gt;
</code></pre>

<p>The typography component is ready for use.</p>

<h4 id="examples">Examples</h4>

<p>A "headline" paragraph.</p>

<pre><code class="html">&lt;p class="mdl-typography--headline"&gt;Regular 24px&lt;/p&gt;
</code></pre>

<p>A "title" paragraph.</p>

<pre><code class="html">&lt;p class="mdl-typography--title"&gt;Medium 20px&lt;/p&gt;
</code></pre>

<p>A "caption" span.</p>

<pre><code class="html">&lt;span class="mdl-typography--caption"&gt;Regular 12px&lt;/span&gt;
</code></pre>

<p>A "button" span.</p>

<pre><code class="html">&lt;span class="mdl-typography--button"&gt;Medium (All Caps) 14px&lt;/span&gt;
</code></pre>

<p>A "display 1" table cell.</p>

<pre><code class="html">&lt;td class="mdl-typography--display-1"&gt;Regular 34px&lt;/td&gt;
</code></pre>

<p>A "body-1" paragraph, also uppercased.</p>

<pre><code class="html">&lt;p class="mdl-typography--body-1 mdl-typography--text-uppercase"&gt;
 This is a standard paragraph, but uppercased.
&lt;/p&gt;
</code></pre>

<blockquote>
  <p><strong>Note:</strong> Because the Roboto font is intended to apply to the entire page, standard "unclassed" HTML elements (e.g., heading levels, divs, paragraphs, spans, tables, etc. with no <code>class</code> attribute) and text modifiers (e.g., strong, em, small, etc.) will use Roboto, while also retaining their inherent and/or inherited characteristics.</p>
  
  <p>Also note that MDL typography provides some automatic adjustments based on its display environment. For example, the <code>body-1</code> style renders at 14px on a mobile device, but 13px on a desktop. You need not do anything to activate these self-modifiers; they are built into the MDL styles.</p>
</blockquote>

<h2 id="configuration-options">Configuration options</h2>

<p>The MDL CSS classes specify the style to use. The table below lists the available classes and their effects.</p>

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
  <td><code>mdl-typography--body-1</code></td>
  <td>Regular 14px (Device), Regular 13px (Desktop)</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--body-1-force-preferred-font</code></td>
  <td>Regular 14px (Device), Regular 13px (Desktop)</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--body-2</code></td>
  <td>Medium 14px (Device), Medium 13px (Desktop)</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--body-2</code></td>
  <td>mdl-typography-body-2</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--body-2-color-contrast</code></td>
  <td>Body with color contrast</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--body-2-force-preferred-font</code></td>
  <td>Medium 14px (Device), Medium 13px (Desktop)</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--button</code></td>
  <td>Medium (All Caps) 14px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--caption</code></td>
  <td>Regular 12px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--caption-color-contrast</code></td>
  <td>Caption with color contrast</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--display-1</code></td>
  <td>Regular 34px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--display-1-color-contrast</code></td>
  <td>Display with color contrast</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--display-2</code></td>
  <td>Regular 45px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--display-3</code></td>
  <td>Regular 56px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--display-4</code></td>
  <td>Light 112px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--headline</code></td>
  <td>Regular 24px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--menu</code></td>
  <td>Medium 14px (Device), Medium 13px (Desktop)</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--subhead</code></td>
  <td>Regular 16px (Device), Regular 15px (Desktop)</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--subhead-color-contrast</code></td>
  <td>Subhead with color contrast</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--table-striped</code></td>
  <td>Striped table</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-capitalize</code></td>
  <td>Capitalized text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-center</code></td>
  <td>Center aligned text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-justify</code></td>
  <td>Justified text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-left</code></td>
  <td>Left aligned text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-lowercase</code></td>
  <td>Lowercased text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-nowrap</code></td>
  <td>No wrap text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-right</code></td>
  <td>Right aligned text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--text-uppercase</code></td>
  <td>Uppercased text</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--title</code></td>
  <td>Medium 20px</td>
  <td>Optional</td>
</tr>
<tr>
  <td><code>mdl-typography--title-color-contrast</code></td>
  <td>Title with color contrast</td>
  <td>Optional</td>
</tr>
</tbody>
</table>
