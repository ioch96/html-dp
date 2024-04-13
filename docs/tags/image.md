# HTML `<img>` Tag

Images can improve the design and the appearance of a web page.

```html
<img src="pic_trulli.jpg" alt="Italian Trulli">
```

The HTML `<img>` tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image.

The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.

The `<img>` tag has two required attributes:

- `src` - Specifies the path to the image
- `alt` - Specifies an alternate text for the image

```html
<img src="url" alt="alternatetext">
```

## The src Attribute

The required src attribute specifies the path (URL) to the image.

**Note**: When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

## The alt Attribute

The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

```html
<img src="img_chania.jpg" alt="Flowers in Chania">
```

**Tip**: A screen reader is a software program that reads the HTML code, and allows the user to "listen" to the content. Screen readers are useful for people who are visually impaired or learning disabled.

## Image as a Link

To use an image as a link, put the `<img>` tag inside the `<a>` tag:

```html
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial">
</a>
```
