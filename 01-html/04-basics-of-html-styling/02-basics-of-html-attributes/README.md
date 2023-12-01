---
title: "Basics Of Styling"
---

# Understanding HTML attributes
Around you are multiple objects with similar functionaly but different physical attributes like slippers of different colours, bag and so on. Something similar is applicable to 
We’ve now understood some basic utilities of HTML Tags, now let's try to understand how we style these HTML tags. Styling is used to control the appearance and behaviour of HTML elements without affecting their functionality. 
We can control aspects like colour, size, font, spacing, and many more qualities that help us make better web pages. 
Let’s take a paragraph tag to understand styling better. Let’s say I have this sentence

```html
<p>I am writing a sentence</p>
```

Style can be applied in the format
```html
<p style=”s1;s2;s3;”> I am writing a sentence </p>
```

Here each of s1/s2/s3 are style updating statements

Let's cover 4 basic styling elements: colour, background colour, font family, and font size.  These are regularly applied to headers and paragraphs.

1. Colour defines the text colour of the HTML element. The property name is "color"
```html
<p style="color:red;">I am writing a sentence in red colour</p>
```
<p style="color:red;">I am writing a sentence in red colour</p>

2. Background colour defines the background colour of the HTML element. The property name is "background-color". As we discussed before the element is a box and this colour will cover the background of the entire box.
```html
<p style="background-color:blue;">I am writing a sentence with blue background</p>
```
<p style="background-color:blue;">I am writing a sentence with blue background</p>

3. Font Family defines the nature of the font used for that HTML element. The property name is "font-family"
```html
<p style="font-family:verdana;">I am writing a sentence in verdana font.</p>
```
<p style="font-family:verdana;">I am writing a sentence in verdana font.</p>

4. Font Size defines the size of the font used for that HTML element. The property name is "font-size". Note that font size can be set in different scales, we are setting in pixels(px) here.
```html
<p style="font-size:30px;">I am writing a sentence with size 3 times the default size</p>
```
<p style="font-size:300px;">I am writing a sentence with size 3 times the default size</p>
  
There are many more styling elements that we would learn with time. We have to keep in mind that all these styling attributes can be applied at once to the HTML element. Let's combine all the styling we have seen above

```html
<p style="color:red;font-size:300%;background-color:blue;font-family:verdana;">
I am writing sentence in red colour and blue background. Is is written in verdana font and has a font size of 3 times the default font size
</p>
```
<p style="color:red;font-size:300%;background-color:blue;font-family:verdana;">I am writing sentence in red colour and blue background. Is is written in verdana font and has a font size of 3 times the default font size</p>
