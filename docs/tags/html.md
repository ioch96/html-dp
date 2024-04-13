# HTML `<html>` Tag

The `<html>` tag represents the root of an HTML document.

The `<html>` tag is the container for all other HTML elements (except for the <!DOCTYPE> tag).

**Note**: You should always include the lang attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

## HTML lang Attribute

The `lang` attribute specifies the language of the element's content.

Common examples are "en" for English, "es" for Spanish, "fr" for French and so on.

The `lang` attribute is a **Global** Attribute, and can be used on any HTML element.

Always use a language attribute on the html tag to declare the default language of the text in the page. This is inherited by all other elements. For example:

```html
<html lang="en">
```

Note that you should use the `html` element rather than the `body` element, since the `body` element doesn't cover the text inside the document's head element.

When the page contains content in another language, add a language attribute to an element surrounding that content. This allows you to style or process it differently. For example:

```html
<p>The title is "<span lang="fr">Le Bon Usage</span>".
```

If your code looks as follows, the language attributes would actually indicate that not only the content but also the `title` attribute text is in Spanish. This is obviously incorrect.

**Bad code. Don't copy!**:

```html
<a lang="es" title="Spanish" href="qa-html-language-declarations.es">Español</a>
```

Instead, move the attribute containing text in a different language to another element, as shown in this example, where the `a` element inherits the default `en` setting of the `html` element.

```html
<html lang="en">
  <a title="Spanish" href="qa-html-language-declarations.es"><span lang="es">Español</span></a>
</html>
```
