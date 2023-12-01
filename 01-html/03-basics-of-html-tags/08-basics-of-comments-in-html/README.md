---
title: "Basic HTML Tags"
---

# Understanding HTML comments

Consider any large software on which multiple people work together, there are chances if you worked on some feature a few months later someone else will work on your code and improve it or maybe even build something on it.
Often, just reading code is not easy to understand the whole system, we need explanations that make us understand the use of different tags and functions. For this purpose, we have HTML comments. Comments are ignored by web browsers and do not affect the rendering of the HTML document. They are purely for the benefit of developers, providing explanations or annotations within the code.

We understand that by reading the comment anyone would know the purpose of the code below it.

```html
<!-- This is a table of cricketers and their top scores -->
<ul>
  <li>Virat Kohli
    <ol>
      <li>165</li>
      <li>145</li>
      <li>135</li>
    </ol>
  </li>
  <li>Rohit Sharma
    <ol>
      <li>185</li>
      <li>155</li>
      <li>125</li>
    </ol>
  </li>
  <li>Babar Azam
    <ol>
      <li>205</li>
      <li>145</li>
      <li>115</li>
    </ol>
  </li>
</ul>
```



Comments can also be added inline
```html
<p>I am writing <!-- comment inside a paragraph -->  a paragraph.</p>
```

A comment can also be in multiple lines
```html
<!--
This is a
multi-line
paragraph comment
-->
<p>I am writing a paragraph.</p>
```
