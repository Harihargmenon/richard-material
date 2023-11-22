---
title: "Basics Of HTML Tags"
---

# Understanding Horizontal Rule/Line Break Tag

Now let’s look at tags used to separate different content pieces in an HTML document. One obvious way of doing with adding a linebreak between 2 tags. The HTML <br> tag is used to insert a line break on a web page. A line break forces the text to start on a new line. Let's understand the code below :
```html
<p> I  am learning how to use line breaks.<br> This still feels very boring. <br> I can’t wait to learn all tags quickly and build my own website </p>
```
This would get displayed as
> I  am learning how to use line breaks.
> This still feels very boring.
> I can’t wait to learn all tags quickly and build my own website 

Please note that here, in case you decided to add these into different paragraph tags, you will observe an extra line before every line.
```html
<p> In am learning how to use line break.</p>
<p>  This still feels very boring.</p>
<p> I can’t wait to learn all tags quickly and build my own website.</p>
```
This would get displayes as
> I  am learning how to use line breaks.
>
> This still feels very boring.
>
> I can’t wait to learn all tags quickly and build my own website 

Another way to do this is by adding a horizontal line to differentiate between different sections. The HTML Horizontal rule tag, <hr>, is used to insert a horizontal line between different elements
```html
<h1>This is the main heading</h1>
<hr>
<h2>This is a subheading</h2> 
```
This would get displayes as
> This is the main heading
> --------------------------------------
> his is a subheading

Note that both these tags have no concept of opening and closing tags. They are referred to as void tags and don’t follow the conventional opening and closing tag structure.
