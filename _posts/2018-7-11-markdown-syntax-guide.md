---
layout: post
title: "GitHub Flavored Markdown: Basic Syntax Guide"
date: 2018-9-15
author: Chris Oung
---

Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform[1].

This document contains a basic overview of the markdown syntax. Use this document as a reference guide for documenting projects on the [GitHub](https://github.com) platform. 

For more advanced information about the markdown syntax, see ["About Writing and Formatting on GitHub"](https://help.github.com/articles/about-writing-and-formatting-on-github/).


### Headings
---

To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the size of the heading[2].

For example, to create a heading level three (<h3>), use three number signs (e.g., ### My Header).

<small>Markdown input:</small>

```
# This is an h1 tag
## This is an h2 tag
### This is an h3 tag
#### This is an h4 tag
##### This is an h5 tag
###### This is an h6 tag
```

<small>HTML output:</small>

```raw
<h1>This is an h1 tag </h1>
<h2>This is an h2 tag</h2>
<h3>This is an h3 tag</h3>
<h4>This is an h4 tag</h4>
<h5>This is an h5 tag</h5>
<h6>This is an h6 tag</h6>
```

<br/>

### Emphasis
---

With markdown, you can add emphasis by making text bold or italic[2].

To bold text, add two asterisks or underscores before and after a word or phrase. To
bold the middle of a word for emphasis, add two asterisks without spaces around the
letters.

<small>Markdown input:</small>

```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

```

<small>HTML output:</small>

```raw
<em>This will be italics</em>
<em>This will also be italics</em>

<strong>This will be bold</strong>
<strong>This will also be bold</strong>
```

<br/>

### Lists
---

You can organize items into ordered and unordered lists.

**Unordered list**

<small>Markdown input:</small>

```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
<small>HTML output:</small>

```raw
<ul>
<li>Item 1</li>
<li>Item 2</li>
<ul>
<li>Item 2a</li>
<li>Item 2b</li>
</ul>
</ul>
```
<br/>

**Ordered list**

<small>Markdown input:</small>

```
1. Item 1
2. Item 2
3. Item 3
   3.1. Item 3a
   3.2. Item 3b
```

<small>HTML output:</small>

```raw
<ol>
<li>Item 1</li>
<li>Item 2</li>
<ol>
<li>Item 2a</li>
<li>Item 2b</li>
</ol>
</ol>
```

<br/>

### Images
---

<small>Markdown input:</small>

```
![GitHub Logo](/images/logo.png)
```

<small>HTML output:</small>

```raw
<img src="/images/logo.png" alt="GitHub Logo"/>
```

<br/>

### Links
---
<small>Markdown input:</small>

```
[GitHub](http://github.com)
```

<small>HTML output:</small>

```raw
<a href="http://github.com">GitHub</a>
```
<br/>

### Code Blocks
---

To create code blocks, indent every line of the block by at least four spaces or one
tab.

<small>Markdown input:</small>

```
<html>
  <head>
  </head>
</html>
```

<small>HTML output:</small>

```raw
<pre>
  <code>
    &lt;html&gt;
    &lt;head&gt;
    &lt;/head&gt;
    &lt;/html&gt;
  </code>
</pre>
```

<br/>

### Blockquote
---

To create a blockquote, add a `>` in front of a paragraph.

<small>Markdown input:</small>

```
> This is a blockquote.
```

<small>HTML output:</small>

```raw
<blockquote>This is a blockquote</blockquote>
```

<br/>


#### References
---

[1]  Source:  _["About Writing and Formatting on GitHub"](https://help.github.com/articles/about-writing-and-formatting-on-github/)_

[2]  Source: _["Basic Writing and Formatting on GitHub"](https://help.github.com/articles/basic-writing-and-formatting-syntax/)_
