---
title: "Advanced HTML Tags"
---

# Understanding Audio Tag

The HTML ```<audio>``` tag is used to embed audio content in a web page. It allows you to include different types of audio files and provides a way for users to play and control the audio directly from the browser.
Let's understand a detailed '''<audio>''' tag implementation and what can be done using it
```html
<audio controls autoplay loop muted volume="0.7">
  <source src="dard-e-disco.mp3" type="audio/mp3">
  <source src="dhoom-machaale.ogg" type="audio/ogg">
  Your browser does not support the audio tag.
  <track src="song_lyrics.vtt" kind="captions" srclang="en" label="English" default>
</audio>
```
Let's understand each part of this code

<strong>controls</strong>: This is used to enable certain functions in the audio tag like autoplay, volume, progress bar, play, pause.

<strong>autoplay</strong>: Initiates automatic playback of the audio when the page loads.

<strong>loop</strong>: Causes the audio to loop continuously.

<strong>muted</strong>: Mutes the audio. If present, the audio will start muted.

<strong>volume</strong>: Sets the initial volume of the audio. The value ranges from 0.0 (mute) to 1.0 (maximum volume). In this example, it's set to 0.7, representing 70% volume.

Now inside the audio tag, there are source tags containing the information about the audio source. The second source tag acts as a backup to the first one.

<strong>src</strong> (inside <source>): Specifies the URL of the audio file.

<strong>type</strong> (inside <source>): Specifies the type of the audio file. It helps the browser understand how to handle the file.

In case your browser does not support an audio tag the final text will be displayed
> This text will be displayed if the browser does not support the audio tag.

Finally, we are aware that most audio tracks are associated with captions/lyrics. The ```<track>``` tag is used for that purpose
<strong><track></strong>: Provides a text track (e.g., captions or subtitles) for the audio.

<strong>src</strong>: Specifies the source of the track file.

<strong>kind</strong>: Indicates the type of text track. In this example, it's set to "captions."

<strong>srclang</strong>: Specifies the language of the track.

<strong>label</strong>: Provides a label for the track.

<strong>default</strong>: Marks the track as the default if multiple tracks are provided.
