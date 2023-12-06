---
title: "Basics Of HTML Tags"
---

# Understanding Anchor Tag

Understanding Anchor Tag
Hyperlinks are links used in HTML to jump from one document to another. The hyperlink in HTML is declared by the ```<a>``` tag. 
A sample  achor tag implementation 
```html
<a href="url">link text</a>
```
Here the attribute href(hypertext reference) contains the document address which we want to jump to.
The colour behaviour of the anchor tag is like : 

An unvisited link is underlined and blue

A visited link is underlined and purple

An active link is underlined and red

The target attribute in anchor tags helps to set where the linked content should be displayed when the user clicks on the link

***_blank***
Opens the linked document in a new browser window or tab. This is often used when you want to make sure the user doesn't leave your site entirely when clicking on a link.
```html
<a href="https://barabariproject.org/" target=”_blank”>Barabari Website</a>
```
***_self***
Default behaviour. The linked document opens in the same frame or window as the current page.
```html
<a href="https://barabariproject.org/" target=”_self”>Barabari Website</a>
```
***_top***
Opens the linked document in the full body of the window, breaking out of any frames.
```html
<a href="https://barabariproject.org/" target=”_top”>Barabari Website</a>
```
We can also use an image as a redirection link
```html
<a href="https://barabariproject.org/">
<img border="0" alt="Barabari Project Logo" src="Barabari_Logo.gif" width="100" height="100">
</a>
```

