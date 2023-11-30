---
title: "Basics Of Styling"
---

# Understanding Favicon Tag

The favicon, short for ***favourite icon*** is a small image that represents a website and is typically displayed in the browser's address bar, tabs, bookmarks, 
and other places where the site's identity is relevant. The HTML ```<link>``` element with the rel attribute set to "icon" is used to define the favicon for a webpage. 

```html
<head>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
```

Let's break down the attributes used in the ```<link>``` tag:

***rel***: Specifies the relationship between the current document and the linked resource. In this case, it's set to "icon" to indicate that the linked resource is an icon.

***href***: Specifies the URL of the linked resource, which is the path to the favicon image file.

***type***: Specifies the MIME type of the linked resource. For favicons, it is usually set to "image/x-icon."
