# zengardenwebsites

Demo: https://www.zengardenwebsites.com

A website in a single HTML file. It simply uses the #anchor suffix and the :target CSS selector to show and hide pages/content.

To create a new page, add a &lt;section&gt; with a unique id:
```
<section id="contact">
   Contact me!
</section>
```
Then you could add a link to it inside &lt;nav&gt;:

```
<a href="#contact">Contact</a>
```
