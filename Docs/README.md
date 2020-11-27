[![Donut's Logo](https://cdn.jsdelivr.net/gh/Wixonic/File@5/GitHub/Donut's%20Logo.png)](https://github.com/Wixonic/Donut/)

> A pure CSS library created by **Wixonic**

<b><ul>
	<li><a href="#intro">Introduction</a></li>
	<li><a href="#start">Start With Donut</a></li>
	<ul>
		<li><a href="#download">Download Donut</a></li>
		<li><a href="#howwork">How Does It Work ?</a></li>
	</ul>
	<li><a href="#style">Stylized Tags</a></li>
	<li><a href="#license">License</a></li>
	<li><a href="#links">Links</a></li>
</ul></b>

<h2 id="intro">Introduction</h2>

**Donut** is a pure CSS library created by **[Wixonic](https://github.com/Wixonic/)**.

<h2 id="start">Start With Donut</h2>

<h3 id="download">Download Donut</h3>

To use Donut, you must first download it.
Copy this to your code :

```html
<link href="https://cdn.jsdelivr.net/gh/Wixonic/Donut@1.0/Donut.css" rel="stylesheet" />
```
				
				<button data-clipboard-text='<link href="https://cdn.jsdelivr.net/gh/{{a}}/{{n}}@{{v}}/{{n}}.css" rel="stylesheet" />' class="copy"><i class="fas fa-copy"></i> Copy</button>
				
			</codeBlock>
			
			<br />
			
			<p>Minified version :</p>
			
			<codeBlock>
				
				<code><red>&#60link</red> <orange>href</orange><red>=</red><green>"https://cdn.jsdelivr.net/gh/{{a}}/{{n}}@{{v}}/{{n}}.min.css"</green> <orange>rel</orange><red>=</red><green>"stylesheet"</green> <red>/&#62</red></code>
				
				<button data-clipboard-text='<link href="https://cdn.jsdelivr.net/gh/{{a}}/{{n}}@{{v}}/{{n}}.min.css" rel="stylesheet" />' class="copy"><i class="fas fa-copy"></i> Copy</button>
				
			</codeBlock>
			
			<br />
			
			<h3 id="howwork">How Does It Work ?</h3>
			
			<p>The {{n}} stylesheet allows you to stylize your page or blocks of your page. To tell CSS that you are using {{n}}, you must put the following tag :</p>
			
			<codeBlock>
				
				<code><red>&#60{{nl}}&#62&#60/{{nl}}&#62</red></code>
				
				<button data-clipboard-text='<{{nl}}></{{nl}}>' class="copy"><i class="fas fa-copy"></i> Copy</button>
				
			</codeBlock>
			
			<br />
			
			<p>After that, you can put any HTML tag in this one :<br />tags will be stylized by {{n}} or non-stylized if they are not included in {{n}}.</p>
			
			<br /><br />
			
			<h2 id="style">Stylized Tags</h2>
			
			<br />
			
			<h1>h1</h1>
			<h2>h2</h2>
			<h3>h3</h3>
			<b>b</b>
			<br />
			<button>button</button>
			<btn>btn</btn>
			<br />
			<a>a</a>
			<br />
			<code>code</code>
			<br />
			<code>code <red>red</red>, <orange>orange</orange> and <green>green</green></code>
			<br />
			<ul>
				
				<li>Unordered list</li>
				<li>With list-items</li>
				<ul>
					
					<li>And up to</li>
					<ul>
						
						<li>Three</li>
						<ul>
							
							<li>Sub-sections</li>
							
						</ul>
						
					</ul>
					
				</ul>
				
			</ul>
			<br />
			<ol>
				
				<li>Ordered list</li>
				<li>With list-items</li>
				<ol>
					
					<li>And up to</li>
					<ol>
						
						<li>Three</li>
						<ol>
							
							<li>Sub-sections</li>
							
						</ol>
						
					</ol>
					
				</ol>
				
			</ol>
			<br />
			<note>note</note>
			<br />
			<note type="comment">with type attribute "comment"</note>
			<br />
			<note type="info">with type attribute "info"</note>
			<br />
			<note type="warning">with type attribute "warning"</note>
			<br />
			<note type="critical">with type attribute "critical"</note>
			
			<br /><br />
			
			<p>You can also use classes with the value the name of the tag you want to apply to any tag (except lists).</p>
			
			<br /><br />
			
			<h2 id="example">Interactive Example</h2>
			
			<p>This is an interactive example, put the code <a onclick="document.getElementById('example-code').focus();">here</a> and see live the result below with the {{n}}'s style !</p>
			
			<codeBlock>
				
				<textarea autocapitalize="none" autocomplete="off" rows="5" spellcheck="false" id="example-code" class="code" oninput="exampleUpdate();">&#60ul&#62
&emsp;
&emsp;&#60li&#62&#60a href="https://www.sololearn.com/">SoloLearn&#60/a&#62&#60/li&#62
&emsp;
&#60/ul&#62</textarea>
				
				<button id="example-copy" class="copy"><i class="fas fa-copy"></i> Copy</button>
				
			</codeBlock>
			
			<br />
			
			<donut id="example-output"></donut>
			
			<br /><br />
			
			<h2 id="license">License</h2>
			
			<br />
			
			<p>{{n}} is available under <a href="https://github.com/{{a}}/{{n}}/blob/Default/Docs/LICENSE.txt">MIT</a> license.</p>
			
			<br /><br />
			
			<h2 id="links">Links</h2>
			
			<br />
			
			<a href="https://github.com/{{a}}/{{n}}" class="btn"><i class="fab fa-github"></i> {{n}}</a>
			<a href="https://github.com/{{a}}" class="btn"><i class="fab fa-github"></i> {{a}}</a>
			
			<br />
			
			<a href="https://developer.mozilla.org/en-US/profiles/{{a}}">{{a}} on MDN</a>
			<br />
			<a href="https://www.sololearn.com/Profile/16606191/?ref=app">{{a}} on SoloLearn</a>
