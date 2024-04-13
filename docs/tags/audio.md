# HTML `<audio>` Tag

The `<audio>` tag is used to embed sound content in a document, such as music or other audio streams.

The `<audio>` tag contains one or more `<source>` tags with different audio sources. The browser will choose the first source it supports.

The text between the `<audio>` and `</audio>` tags will only be displayed in browsers that do not support the `<audio>` element.

```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  <p>Your browser does not support the audio tag.</p>
</audio>
```

There are three supported audio formats in HTML: MP3, WAV, and OGG.

|Browser|MP3|WAV|OGG|
|:-|:-:|:-:|:-:|
|Edge/IE|YES|YES*|YES*|
|Chrome|YES|YES|YES|
|Firefox|YES|YES|YES|
|Safari|YES|YES|NO|
|Opera|YES|YES|YES|

*From Edge 79
