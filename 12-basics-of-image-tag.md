---
title: "Basics Of HTML Tags"
---

# Understanding Image Tag

The HTML <img> tag is used to insert an image into a web page. It is an empty element, meaning that it does not have a closing tag.
To use the <img> tag, simply add it to your HTML code and specify the following attributes:
src: The URL/path of the image.
alt: A text description of the image. This is used for accessibility purposes and will be displayed if the image cannot be loaded. The screen reader uses this text to describe the image.
<img src="https://barabariproject.org/favicon.png" alt="Barabari Logo">

This is the location where the browser can find the image file and download it to display on the web page. Now we must note that this location can either be the URL of the image of a relative address w.r.t the file where the image tag is used.
<img src="/images/imageOfSpiderman.gif" alt="Spiderman" style="width:128px;height:128px;">
Here the image of Spiderman is within the same file system in a different directory. Going forward we will work on styling images in more detail.

