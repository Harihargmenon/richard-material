---
title: "Basics Of Element Layouts"
---

# Block-Inline Elements

## Block Elements
Block-level elements are HTML tags that create a new "block" or a rectangular section on a web page. These elements typically start on a new line and stretch across the full width of their container (like a paragraph of text or a section of the page).  
Some examples of block elements are :
> - Headings (```<h1>``` through ```<h6>```)
> - Paragraphs (```<p>```)
> - Divisions (```<div>```)
> - Lists (```<ul>``` and ```<ol>```)
>  - Images (```<img>```)
> - Tables (```<table>```)

## Inline Elements

Inline-level elements, on the other hand, do not create a new block or start on a new line. They flow within the content, appearing on the same line as the surrounding text or elements. Some examples of inline elements are 
> - Spans (```<span>```)
> - Anchors (```<a>```)
> - Strong and emphasis (```<strong>``` and ```<em>```)
> - Images (```<img>``` if the width and height attributes are specified)
> - Form elements (```<input>``` and ```<button>```)

Block-level elements and inline elements can be combined to create complex and visually appealing web pages. For example, you could use a block-level element to create a heading for a section of your page, and an inline element to create a link within the heading.

Here is an example of how to use block-level and inline elements together:
```html
<h1> This is the Barabari Project  <a href="https://barabariproject.org/">Website</a></h1>
```

In this example, the ```<h1>``` tag is a block-level element, so it will start on a new line and take up the full width of the page. The <a> tag is an inline element, so it will appear on the same line as the ```<h1>``` tag. Note that we will learn about all these tags in detail in the coming sections.

## Inline Block Elements
Inline-block elements are a combination of inline and block elements. They flow within the content like inline elements but can have block-level properties like setting width and height. This is useful when you want elements to appear inline but also have some block-level properties.

When we learn about the styling of elements, we'll discuss how inline blocks are declared.
