# HTML `<code>` Tag

The `<code>` tag is used to define a piece of computer code. The content inside is displayed in the browser's default monospace font.

**Tip**: This tag is not deprecated. However, it is possible to achieve richer effect by using CSS.

```html
<p>The HTML <code>button</code> tag defines a clickable button.</p>
<p>The CSS <code>background-color</code> property defines the background color of an element.</p>
```

To represent multiple lines of code, wrap the `<code>` element within a `<pre>` element. The `<code>` element by itself only represents a single phrase of code or line of code.

```html
<pre><code>
  public class Main {
    public static void main(String[] args) {
      System.out.println("Hello World!");
    }
  }
</code></pre>
```
