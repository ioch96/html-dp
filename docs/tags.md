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
|`<p>`|Defines a paragraph|block|[here](../examples/paragraph.html)|x|
|`<h1> to <h6>`|Defines HTML headings|block|[here](../examples/headings.html)||
|`<meta>`|Defines metadata about an HTML document| |[here](../examples/metadata.html)||
|`<strong>`|Defines important text|inline|[here](../examples/strong.html)||
|`<small>`|Defines smaller text|inline|[here](../examples/small.html)||
|`<details>`|Defines additional details that the user can view or hide| |[here](../examples/details.html)||
|`<li>`|Defines a list item|block|[here](../examples/unordered_list.html)||
|`<ol>`|Defines an ordered list|block|[here](../examples/ordered_list.html)||
|`<ul>`|Defines an unordered list|block|[here](../examples/unordered_list.html)||
|`<dl>`|Defines a description list|block|[here](../examples/description_list.html)||
|`<dt>`|Defines a term/name in a description list|block|[here](../examples/description_list.html)||
|`<dd>`|Defines a description/value of a term in a description list|block|[here](../examples/description_list.html)||
|`<br>`|Defines a single line break|inline|[here](../examples/break.html)||
|`<hr>`|Defines a thematic change in the content|block|[here](../examples/horizontal_rule.html)||
|`<summary>`|Defines a visible heading for a `<details>` element| |[here](../examples/details.html)||
|`<b>`|Defines bold text|inline|[here](../examples/bold.html)||
|`<cite>`|Defines the title of a work|inline|[here](../examples/cite.html)|x|
|`<blockquote>`|Defines a section that is quoted from another source|block|[here](../examples/blockquote.html)|x|
|`<em>`|Defines emphasized text|inline|[here](../examples/emphasized.html)|x|
|`<i>`|Defines a part of text in an alternate voice or mood|inline|[here](../examples/italic.html)|x|
|`<sub>`|Defines subscripted text|inline|[here](../examples/subscript.html)|x|
|`<sup>`|Defines superscripted text|inline|[here](../examples/superscript.html)|x|
|`<time>`|Defines a specific time (or datetime)|inline|[here](../examples/time.html)||
|`<header>`|Defines a header for a document or section|block|[here](../examples/semantic_structure.html)||
|`<nav>`|Defines navigation links|block|[here](../examples/nav.html)||
|`<aside>`|Defines content aside from the page content|block|[here](../examples/semantic_structure.html)||
|`<main>`|Specifies the main content of a document|block|[here](../examples/semantic_structure.html)||
|`<section>`|Defines a section in a document|block|[here](../examples/section.html)||
|`<article>`|Defines an article|block|[here](../examples/semantic_structure.html)||
|`<footer>`|Defines a footer for a document or section|block|[here](../examples/semantic_structure.html)||
|`<div>`|Defines a section in a document|block|[here](../examples/div.html)||
|`<span>`|Defines a section in a document|inline|[here](../examples/span.html)||
|`<a>`|Defines a hyperlink|inline|[here](../examples/anchor.html)||
|`<abbr>`|Defines an abbreviation or an acronym|inline|[here](../examples/abbreviation.html)|x|

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

## HTML `<h1>...<h6>` Tag

Avoid using multiple `<h1>` elements on one page.

While using multiple `<h1>` elements on one page is allowed by the HTML standard (as long as they are not nested), this is not considered a best practice. A page should generally have a single `<h1>` element that describes the content of the page.

Prefer using only one `<h1>` per page and nest headings without skipping levels.

## HTML `<abbr>` Tag

The `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".

**Tip**: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element.

## Basic Website Layout

![Semantic Structure](../images/semantic_structure.png)

## HTML Block and Inline Elements

Every HTML element has a default display value, depending on what type of element it is.

The two most common display values are block and inline.

## Block-level Elements

A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

## Inline Elements

An inline element does not start on a new line. An inline element only takes up as much width as necessary.

**Note**: An inline element cannot contain a block-level element!

## The `<div>` Element

The `<div>` element is often used as a container for other HTML elements. The `<div>` element has no required attributes, but style, class and id are common. When used together with CSS, the `<div>` element can be used to style blocks of content.

## The `<span>` Element

The `<span>` element is an inline container used to mark up a part of a text, or a part of a document The `<span>` element has no required attributes, but style, class and id are common.
