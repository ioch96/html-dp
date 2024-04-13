# HTML `<video>` Tag

The `<video>` tag is used to embed video content in a document, such as a movie clip or other video streams.

The `<video>` tag contains one or more `<source>` tags with different video sources. The browser will choose the first source it supports.

The text between the `<video>` and `</video>` tags will only be displayed in browsers that do not support the `<video>` element.

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  <p>Your browser does not support the video tag.</p>
</video>
```

There are three supported video formats in HTML: MP4, WebM, and OGG.

|Browser|MP4|WebM|Ogg|
|:-|:-:|:-:|:-:|
|Edge|YES|YES|YES|
|Chrome|YES|YES|YES|
|Firefox|YES|YES|YES|
|Safari|YES|YES|NO|
|Opera|YES|YES|YES|
