---
title: "Advanced HTML Tags"
---

# Understanding Iframes
The ```<iframe>``` stands for inline frame, this HTML tag is used to embed another document or webpage within the current HTML document. It allows you to include content from another source, such as a video, map, or another webpage, into your own webpage
Let's analyze a basic iframe implementation
```html
<iframe src="URL" width="width" height="height" frameborder="0" title="Descriptive Title"></iframe>
```

Let's understad each aspect of this code
iframe: The tag used to add the iframe

<strong>src</strong>: Specifies the URL of the content to be displayed within the frame. This can be a relative or absolute URL. Similar to what we have already learnt in image and video tag

<strong>width and height</strong>: These attributes set the width and height of the iframe. You can specify them in pixels or as a percentage of the parent container.

<strong>frameborder</strong>: This attribute determines whether or not to display a border around the iframe. Setting it to "0" removes the border, while "1" displays it.

<strong>title</strong>: This attribute provides a descriptive text about the content within the iframe. It is crucial for accessibility and is displayed when a user hovers over the iframe or if the iframe content cannot be loaded.

This is how the iframe gets displayed on to our main HTML file
<iframe src="https://barabariproject.org/" width="10" height="20" frameborder="0" title="Barabari Website"></iframe>

Now that you have basic idea about iframes let's dig deeper into 2 more attributes

<strong>srcdoc</strong>: Instead of a website URL, we can send HTML directly to the iframe, which will be displayed instead of another website. For example,
```html
<iframe srcdoc="<h1>This is an HTML tutorial on iframes/h1>"></iframe>
```
<strong>name</strong>: The name attribute is used to specify the name for an ```<iframe>```. It can be used as a target for other HTML elements like the ```<a>``` tag. For example,
```html
<iframe src="https://barabariproject.org/" name="iframe_target" height="500" width="400"></iframe>
<a href="https://www.google.com/" target="iframe_target">Switch to Google</a>
```
<iframe src="https://barabariproject.org/" name="iframe_target" height="500" width="400"></iframe>
<a href="https://www.google.com/" target="iframe_target">Switch to Google</a>

So here on clicking on the anchor tag the iframe changes frmo Barabari Website to Google Website.

Go ahead, try how to embed videos onto your website from youtube using iframes.
