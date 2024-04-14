# HTML `<h1>...<h6>` Tag

HTML headings are titles or subtitles that you want to display on a webpage.

HTML headings are defined with the `<h1>` to `<h6>` tags.

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

**Note**: Browsers automatically add some white space (a margin) before and after a heading.

## Headings Are Important

Search engines use the headings to index the structure and content of your web pages.

Users often skim a page by its headings. It is important to use headings to show the document structure.

`<h1>` headings should be used for main headings, followed by `<h2>` headings, then the less important `<h3>`, and so on.

**Note**: Use HTML headings for headings only. Don't use headings to make text BIG or bold.

## Avoid using multiple `<h1>` elements on one page

While using multiple `<h1>` elements on one page is allowed by the HTML standard (as long as they are not nested), this is not considered a best practice. A page should generally have a single `<h1>` element that describes the content of the page.

Prefer using only one `<h1>` per page and nest headings without skipping levels.

## Bigger Headings

Each HTML heading has a default size. However, you can specify the size for any heading with the `style` attribute, using the CSS `font-size` property:

```html
<h1 style="font-size:60px;">Heading 1</h1>
```
