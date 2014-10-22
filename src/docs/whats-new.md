# What's new in version 4?

<dl>
	<dt>SVG Support</dt>
	<dd>Kraken now features an SVG sprite generator, as well as an SVG feature test for some conditional styling.</dd>
</dl>

<dl>
	<dt>Goodbye IE 8</dt>
	<dd>Kraken 4 drops optimization for IE 8. That means no more conditional classes on the <code>&lt;html&gt;</code> element, and <a href="https://code.google.com/p/html5shim/">HTML5 shim</a> has been removed. IE 8 users will get a very minimal, content-focused, single-column experience.</dd>
</dl>

<dl>
	<dt>Documentation Generator</dt>
	<dd>A built-in documentation generator makes it easier for you to keep your team informed and teach clients about how to use the things you build with Kraken.</dd>
</dl>

<dl>
	<dt>Sass 3 Features</dt>
	<dd>Sass variables and the new <code>@each</code> loop make extending the grid and adding icon fonts much easier.</dd>
</dl>

<dl>
	<dt>New Namespacing</dt>
	<dd>The feature detection script was renamed <code>detects.js</code>. The main CSS and JavaScript files were namespaced as <code>main</code> instead of <code>kraken</code>. And <code>.text-tall</code> was changed to <code>.text-large</code> for better semantics and extensibility.</dd>
</dl>