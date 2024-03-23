# The most important HTML tags in an overview

HTML tags or commands are used when building a website and they store the most important information for all browsers. In addition to HTML tags for the basic structure, there are also some that you can use to include media, create forms, or set the typeface.

## What are HTML tags?

If you want to learn HTML or write your own HTML code, HTML tags are probably your most important and effective tool. The HTML commands are used to pass information to the different browsers. This way the website is structured in the best possible way and can be displayed by every browser due to the information stored.

HTML tags are represented by a start and an end tag. The HTML commands are placed in angle brackets and contain the desired information, with the end tag being marked by a slash. The combination of start tag, information and end tag is called an element. It is possible to assign an HTML attribute to the element, which contributes further information.

## HTML Tags

|Tag|Description|Type|Example|Doc|
|:-:|:-|:-:|:-:|:-:|
|`<!--...-->`|Defines a comment| |[here](../examples/comment.html)||
|`<!DOCTYPE>`|Defines the document type| |[here](../examples/basic.html)||
|`<html>`|Defines the root of an HTML document| |[here](../examples/basic.html)||
|`<head>`|Contains metadata/information for the document| |[here](../examples/basic.html)||
|`<body>`|Defines the document's body| |[here](../examples/basic.html)||
|`<title>`|Defines a title for the document| |[here](../examples/title.html)||
|`<p>`|Defines a paragraph| |[here](../examples/paragraph.html)|x|
|`<h1> to <h6>`|Defines HTML headings| |[here](../examples/headings.html)||
|`<meta>`|Defines metadata about an HTML document| |[here](../examples/metadata.html)||
|`<strong>`|Defines important text| |[here](../examples/strong.html)||
|`<small>`|Defines smaller text| |[here](../examples/small.html)||
|`<details>`|Defines additional details that the user can view or hide| |[here](../examples/details.html)||
|`<li>`|Defines a list item| |[here](../examples/unordered_list.html)||
|`<ol>`|Defines an ordered list| |[here](../examples/ordered_list.html)||
|`<ul>`|Defines an unordered list| |[here](../examples/unordered_list.html)||
|`<dl>`|Defines a description list| |[here](../examples/description_list.html)||
|`<dt>`|Defines a term/name in a description list| |[here](../examples/description_list.html)||
|`<dd>`|Defines a description/value of a term in a description list| |[here](../examples/description_list.html)||
|`<br>`|Defines a single line break| |[here](../examples/break.html)||
|`<hr>`|Defines a thematic change in the content| |[here](../examples/horizontal_rule.html)||
|`<summary>`|Defines a visible heading for a `<details>` element| |[here](../examples/details.html)||
|`<b>`|Defines bold text| |[here](../examples/bold.html)||
|`<cite>`|Defines the title of a work| |[here](../examples/cite.html)|x|
|`<blockquote>`|Defines a section that is quoted from another source| |[here](../examples/blockquote.html)|x|
|`<em>`|Defines emphasized text| |[here](../examples/emphasized.html)|x|
|`<i>`|Defines a part of text in an alternate voice or mood| |[here](../examples/italic.html)|x|
|`<sub>`|Defines subscripted text| |[here](../examples/subscript.html)|x|
|`<sup>`|Defines superscripted text| |[here](../examples/superscript.html)|x|
|`<time>`|Defines a specific time (or datetime)| | ||
|`<header>`|Defines a header for a document or section| |[here](../examples/semantic_structure.html)||
|`<nav>`|Defines navigation links| |[here](../examples/nav.html)||
|`<aside>`|Defines content aside from the page content| |[here](../examples/semantic_structure.html)||
|`<main>`|Specifies the main content of a document| |[here](../examples/semantic_structure.html)||
|`<section>`|Defines a section in a document| | ||
|`<article>`|Defines an article| |[here](../examples/semantic_structure.html)||
|`<footer>`|Defines a footer for a document or section| |[here](../examples/semantic_structure.html)||
|`div`|Defines a section in a document| |[here](../examples/div.html)||
|`span`|Defines a section in a document| |[here](../examples/span.html)||

## HTML `<cite>` Tag

The `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

**Note**: A person's name is not the title of a work.

The text in the `<cite>` element usually renders in *italic*.

## HTML `<blockquote>` Tag

The `<blockquote>` tag specifies a section that is quoted from another source.

Browsers usually indent `<blockquote>` elements.

## HTML `<em>` Tag

The `<em>` tag is used to define emphasized text. The content inside is typically displayed in italic.

A screen reader will pronounce the words in `<em>` with an emphasis, using verbal stress.

## HTML `<p>` Tag

The `<p>` tag defines a paragraph.

Browsers automatically add a single blank line before and after each `<p>` element.

The `<p>` element represents a paragraph. It cannot contain **block-level** elements (including `<p>` itself).

Reference: [https://www.w3.org/TR/html401/struct/text.html#h-9.3.1](https://www.w3.org/TR/html401/struct/text.html#h-9.3.1)

## HTML `<i>` Tag

The `<i>` tag defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.

The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

## HTML `<sub>` Tag

The `<sub>` tag defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O.

**Tip**: Use the `<sup>` tag to define superscripted text.

## HTML `<sup>` Tag

The `<sup>` tag defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1].

## HTML `<h1>...<h6>`

Avoid using multiple `<h1>` elements on one page.

While using multiple `<h1>` elements on one page is allowed by the HTML standard (as long as they are not nested), this is not considered a best practice. A page should generally have a single `<h1>` element that describes the content of the page.

Prefer using only one `<h1>` per page and nest headings without skipping levels.

## Basic Website Layout

![Semantic Structure](../images/semantic_structure.png)

## HTML Escape Characters

URL: `https://mateam.net/html-escape-characters`

|Number|Symbol|Entity Name|Code|Description|
|:----:|:----:|:---------:|:--:|:---------:|
|34|`“`|`&quot;`|`&#34;`|Quotation mark|
|38|`&`|`&amp;`|`&#38;`|Ampersand|
|39|`‘`||`&#39;`|Apostrophe|
|60|`<`|`&alt;`|`&#60;`|Less-than|
|62|`>`|`&gt;`|`&#62;`|Greater than|
|160|``|`&nbsp;`|`&#160;`|Non-breaking space|
