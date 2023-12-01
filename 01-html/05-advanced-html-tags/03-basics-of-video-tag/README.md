---
title: "Advanced HTML Tags"
---

# Understanding Video Tag
The HTML ```<video>``` element is used to embed video content in a document. It supports various attributes and functionalities to control the appearance and behaviour of the video player. 
Let's understand a detailed '''<video>''' tag implementation and what can be done using it

```html
<!-- Enhanced Video Tag -->
<video controls
       width="600"
       height="400"
       poster="thumbnail.jpg"
       autoplay
       loop
       muted
>
  <!-- Source Attributes -->
  <source src="example.mp4" type="video/mp4">
  <source src="example.webm" type="video/webm">
  Your browser does not support the video tag.
</video>
```
Let's understand each part of this code
```<video>```: The video element, which embeds a video in the document.

controls: Used to add playback controls (play, pause, volume, etc.).

width and height attributes: Set the dimensions of the video player.

poster attribute: Specifies an image to be displayed before playback.

autoplay attribute: Starts playing the video automatically.

loop attribute: Makes the video loop.

muted attribute: Mutes the audio by default.

Now inside the audio tag, there are source tags containing the information about the audio source. The second source tag acts as a backup to the first one.

<strong>src</strong> (inside <source>): Specifies the source of the video file.

<strong>type</strong> (inside <source>): Specifies the type of the video file. It helps the browser understand how to handle the file.

In case your browser does not support an audio tag the final text will be displayed
> Your browser does not support the video tag.

