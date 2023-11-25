---
title: "Basics Of Styling"
---

# Understanding Parent Child Tag Relationship

As we have learned before, HTML tags can be nested one inside another, the outer tag is the parent tag and the inner tag is the child tag. While styling, often some styles are passed from parent to child tag. 
For Example, let's take the example of a list with the parent tag containting a text colour of red.

```html
<ul style="color:red">
    <li>Python</li>
    <li>JavaScript</li>
    <li>C++</li>
</ul>
```
Here each list element ```<li>``` is the child element of the ```<ul>``` element and will default get a red colour.
Whenever we give specific styling to child element, then that takes precedence over the parent element styling. For example : 

```html
<ul style="color:red">
    <li style="color:blue">Python</li>
    <li>JavaScript</li>
    <li>C++</li>
</ul>
```
Here “Python” would be in blue.
Please note that all styling attributes are not passed on to the children tags. So always check and confirm how specific attributes are passed on.
