---
layout: post
title: "GitHub Flavored Markdown Syntax Guide"
date: 2019-3-11
author: Chris Oung
---

**Table of Contents**

1. [Introduction](#introduction)
2. [Headings](#headings)
3. [Emphasis](#emphasis)
4. [Lists](#lists)
5. [Images](#images)
6. [Links](#links)
7. [Code Blocks](#code-blocks)
8. [Blockquotes](#blockquotes)
9. [References](#references)

<br/>

## Introduction <a name="introduction"></a>

Markdown is a lightweight and an easy-to-use syntax for styling all forms of writing on the [GitHub](https://github.com) platform. This document contains a basic overview of the markdown syntax. Use this document as a reference guide for documenting projects on the GitHub platform. 

For more advanced information about the markdown syntax, see [About Writing and Formatting on GitHub](https://help.github.com/articles/about-writing-and-formatting-on-github/).

<br/>

## Headings <a name="headings"></a>

To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the size of the heading.[2]

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
<h1>This is an h1 tag</h1>
<h2>This is an h2 tag</h2>
<h3>This is an h3 tag</h3>
<h4>This is an h4 tag</h4>
<h5>This is an h5 tag</h5>
<h6>This is an h6 tag</h6>
```

<br/>

## Emphasis <a name="emphasis"></a>

With markdown, you can add emphasis by making text bold or italic.[2]

To bold text, add two asterisks or underscores before and after a word or phrase. 

<small>Markdown input:</small>

```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

```

<small>HTML output:</small>

```raw
<em>This will be italic</em>
<em>This will also be italic</em>

<strong>This will be bold</strong>
<strong>This will also be bold</strong>
```

<br/>

## Lists <a name="lists"></a>

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
<li>Item 3</li>
<ol>
<li>Item 3a</li>
<li>Item 3b</li>
</ol>
</ol>
```

<br/>

## Images <a name="images"></a>

<small>Markdown input:</small>

```
![GitHub Logo](/images/logo.png)
```

<small>HTML output:</small>

```raw
<img src="/images/logo.png" alt="GitHub Logo"/>
```

<br/>

## Links <a name="links"></a>

<small>Markdown input:</small>

```
[GitHub](http://github.com)
```

<small>HTML output:</small>

```raw
<a href="http://github.com">GitHub</a>
```
<br/>

## Code Blocks <a name="code-blocks"></a>

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

## **Blockquote** <a name="blockquotes"></a>

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

**References** <a name="references"></a>

[1]  Source: ["About Writing and Formatting on GitHub"](https://help.github.com/articles/about-writing-and-formatting-on-github/)

[2]  Source: ["Basic Writing and Formatting on GitHub"](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
