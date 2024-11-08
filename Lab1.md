<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lab 1</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><hr>
<p>University of Souk Ahras<br>
Computer Science Department<br>
Course: Web Technologies / M1 WIA</p>
<h1 id="lab-1-exploring-the-basics-of-web-technologies">Lab 1: Exploring the Basics of Web Technologies</h1>
<h3 id="guidance">Guidance</h3>
<p>This lab is designed for Master 1 students to practice the Web Technologies course under the guidance of Dr. Zakaria Gheid.</p>
<h3 id="objective">Objective</h3>
<p>By the end of this lab, students will understand the evolution of the web, practice basic HTML and CSS, explore the client-server model, and deploy a simple webpage using a hosting service.</p>
<h3 id="prerequisites">Prerequisites</h3>
<ul>
<li>Basic understanding of HTML and CSS.</li>
<li>Knowledge of basic command-line operations.</li>
<li>Git version control knowledge (optional).</li>
</ul>
<h3 id="lab-report">Lab Report</h3>
<ul>
<li>The final version of the HTML, and CSS files.</li>
<li>A link to GitHub repository or deployed site.</li>
</ul>
<hr>
<h3 id="exercise-1-building-a-simple-static-webpage-web-1.0">Exercise 1: Building a Simple Static Webpage (Web 1.0)</h3>
<ol>
<li>
<p><strong>Create a static HTML page</strong> that includes a title, a few paragraphs, an image, and some links. This page should follow the “Web 1.0” structure.</p>
<p><strong>Requirements</strong>:</p>
<ul>
<li>Use a simple HTML layout.</li>
<li>Add headings, paragraphs, and links.</li>
<li>Include an image.</li>
</ul>
<p><strong>Sample Code</strong>:</p>
<pre class=" language-html"><code class="prism  language-html"><span class="token doctype">&lt;!DOCTYPE html&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span> <span class="token attr-name">lang</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>en<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>meta</span> <span class="token attr-name">charset</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>UTF-8<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>title</span><span class="token punctuation">&gt;</span></span>My Static Webpage<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>title</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Welcome to My Webpage<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>This is a static webpage showcasing Web 1.0 features.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>img</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>path/to/image.jpg<span class="token punctuation">"</span></span> <span class="token attr-name">alt</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>Sample Image<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>Visit <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>a</span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>https://example.com<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Example<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>a</span><span class="token punctuation">&gt;</span></span> for more information.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span>
</code></pre>
</li>
<li>
<p><strong>Open the HTML file in a browser</strong> to verify its appearance.</p>
</li>
</ol>
<hr>
<h3 id="exercise-2-dynamic-content-with-javascript-web-2.0">Exercise 2: Dynamic Content with JavaScript (Web 2.0)</h3>
<ol>
<li>
<p>Add <strong>basic interactivity</strong> to the webpage using JavaScript. Create a button that changes the text content on the page when clicked, emulating the dynamic nature of Web 2.0.</p>
<p><strong>Requirements</strong>:</p>
<ul>
<li>Create a button.</li>
<li>Write a JavaScript function that modifies the page content.</li>
</ul>
<p><strong>Sample Code</strong>:</p>
<pre class=" language-html"><code class="prism  language-html"><span class="token doctype">&lt;!DOCTYPE html&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span> <span class="token attr-name">lang</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>en<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>meta</span> <span class="token attr-name">charset</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>UTF-8<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>title</span><span class="token punctuation">&gt;</span></span>Interactive Webpage<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>title</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Welcome to My Interactive Webpage<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>message<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Click the button to change this text.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">onclick</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>changeText()<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Click Me<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span><span class="token punctuation">&gt;</span></span><span class="token script language-javascript">
    <span class="token keyword">function</span> <span class="token function">changeText</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
      document<span class="token punctuation">.</span><span class="token function">getElementById</span><span class="token punctuation">(</span><span class="token string">"message"</span><span class="token punctuation">)</span><span class="token punctuation">.</span>innerText <span class="token operator">=</span> <span class="token string">"You clicked the button!"</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
  </span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span>
</code></pre>
</li>
<li>
<p><strong>Test the interactivity</strong> by opening the HTML file in your browser and clicking the button to see the text change.</p>
</li>
</ol>
<hr>
<h3 id="exercise-3-basic-css-styling">Exercise 3: Basic CSS Styling</h3>
<ol>
<li>
<p>Add a <strong>CSS file</strong> to style your HTML content. Use colors, font styles, and layout properties to make your webpage visually appealing.</p>
<p><strong>Requirements</strong>:</p>
<ul>
<li>Create a CSS file to apply styles.</li>
<li>Use colors, font styles, and basic layout adjustments.</li>
</ul>
<p><strong>Sample Code (HTML)</strong>:</p>
<pre class=" language-html"><code class="prism  language-html"><span class="token doctype">&lt;!DOCTYPE html&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span> <span class="token attr-name">lang</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>en<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>meta</span> <span class="token attr-name">charset</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>UTF-8<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>title</span><span class="token punctuation">&gt;</span></span>Styled Webpage<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>title</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>link</span> <span class="token attr-name">rel</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>stylesheet<span class="token punctuation">"</span></span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>style.css<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Welcome to My Styled Webpage<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>This is a paragraph with some styling applied.<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span>
</code></pre>
</li>
<li>
<p><strong>Link the bellow CSS file</strong> to your HTML file as shown above.</p>
<p><strong>CSS (style.css)</strong>:</p>
<pre class=" language-css"><code class="prism  language-css"><span class="token selector">body </span><span class="token punctuation">{</span>
  <span class="token property">font-family</span><span class="token punctuation">:</span> Arial, sans-serif<span class="token punctuation">;</span>
  <span class="token property">background-color</span><span class="token punctuation">:</span> <span class="token hexcode">#f0f8ff</span><span class="token punctuation">;</span>
  <span class="token property">color</span><span class="token punctuation">:</span> <span class="token hexcode">#333</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token selector">h1 </span><span class="token punctuation">{</span>
  <span class="token property">color</span><span class="token punctuation">:</span> <span class="token hexcode">#2a6ebb</span><span class="token punctuation">;</span>
  <span class="token property">text-align</span><span class="token punctuation">:</span> center<span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token selector">p </span><span class="token punctuation">{</span>
  <span class="token property">font-size</span><span class="token punctuation">:</span> <span class="token number">1.2</span>em<span class="token punctuation">;</span>
  <span class="token property">color</span><span class="token punctuation">:</span> <span class="token hexcode">#555</span><span class="token punctuation">;</span>
  <span class="token property">margin</span><span class="token punctuation">:</span> <span class="token number">20</span>px<span class="token punctuation">;</span>
  <span class="token property">text-align</span><span class="token punctuation">:</span> justify<span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
</li>
<li>
<p><strong>Open</strong> the HTML file in a browser to see the applied styling.</p>
</li>
</ol>
<hr>
<h3 id="exercise-4-deploying-a-static-website-using-github-pages">Exercise 4: Deploying a Static Website Using GitHub Pages</h3>
<ol>
<li>
<p><strong>Objective</strong>: Deploy a simple static website using GitHub Pages. By the end of this exercise, you will have a live website accessible on the internet.</p>
</li>
<li>
<p><strong>Instructions</strong>:</p>
<ul>
<li>Prepare your basic HTML and CSS files for deployment.</li>
<li>Use GitHub Pages to host your project online.</li>
<li>Verify your website is accessible via the provided GitHub Pages URL.</li>
</ul>
</li>
<li>
<p><strong>Steps</strong>:</p>
<h4 id="step-1-setting-up-your-project">Step 1: Setting Up Your Project</h4>
<ul>
<li>Rename your HTML file to <code>index.html</code>.</li>
<li>Place all files (HTML, CSS) in a single folder.</li>
</ul>
<h4 id="step-2-creating-a-github-repository">Step 2: Creating a GitHub Repository</h4>
<ul>
<li>If you don’t have a GitHub account, create one at <a href="https://github.com">GitHub</a>.</li>
<li>Log in to GitHub and create a new repository by clicking the <strong>New</strong> button.</li>
<li>Name the repository (e.g., <code>my-static-website</code>) and choose the <strong>Public</strong> option.</li>
<li>Initialize the repository with a <strong>README file</strong> if you wish, but do not add any <code>.gitignore</code> or license files.</li>
</ul>
<h4 id="step-3-uploading-files">Step 3: Uploading Files</h4>
<ul>
<li>Once your repository is created, click <strong>Add file &gt; Upload files</strong> to add your HTML, CSS, and any additional files to the repository.</li>
<li>Commit the changes by clicking <strong>Commit changes</strong> after uploading your files.</li>
</ul>
<h4 id="step-4-activating-github-pages">Step 4: Activating GitHub Pages</h4>
<ul>
<li>Go to the <strong>Settings</strong> tab of your repository.</li>
<li>Scroll down to the <strong>Pages</strong> section.</li>
<li>Under <strong>Source</strong>, select the branch that contains your <code>index.html</code> file (usually <code>main</code> or <code>master</code>).</li>
<li>GitHub will automatically generate a URL for your website, which will be accessible at <code>https://username.github.io/repository-name</code> (replace <code>username</code> with your GitHub username and <code>repository-name</code> with your repository name).</li>
</ul>
</li>
</ol>
<hr>
</div>
</body>

</html>
