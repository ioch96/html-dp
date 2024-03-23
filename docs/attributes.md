# HTML Attribute Reference

The table below lists all HTML attributes and what elements they can be used within:

|Attribute|Belongs to|Description|
|:-:|:-:|:-|
|charset|`<meta>`|Specifies the character encoding|
|datetime|`<time>`|Specifies the date and time|
|title|`<abbr>`|Shows the description for the abbreviation/acronym when you mouse over the element|

|download|`<a>`|Specifies that the target will be downloaded when a user clicks on the hyperlink|
|href|`<a>`|Specifies the URL of the page the link goes to|
|target|`<a>`|Specifies the target for where to open the linked document or where to submit the form|
|start|`<ol>`|Specifies the start value of an ordered list|
|reversed|`<ol>`|Specifies that the list order should be descending (9,8,7...)|

## HTML `<meta>` charset Attribute

The charset attribute specifies the character encoding for the HTML document.

The HTML5 specification encourages web developers to use the UTF-8 character set, which covers almost all of the characters and symbols in the world!

```html
<head>
  <meta charset="UTF-8">
</head>
```

## HTML `<time>` datetime Attribute

The datetime attribute represent a machine-readable format of a `<time>` element.

Examples of valid datetime values:

```html
Dates:
<time datetime="1914">  <!-- means the year 1914 -->
<time datetime="1914-12">  <!-- means December 1914 -->
<time datetime="1914-12-20">  <!-- means 20 December 1914 -->
<time datetime="12-20">  <!-- means 20 December any year -->
<time datetime="1914-W15">  <!-- means week 15 of year 1914 -->

Date and Times:
<time datetime="1914-12-20T08:00">  <!-- means 20 December 1914 at 8am -->
<time datetime="1914-12-20 08:00">  <!-- also means 20 December 1914 at 8am -->
<time datetime="1914-12-20 08:30:45">  <!-- with minutes and seconds -->
<time datetime="1914-12-20 08:30:45.687">  <!-- with minutes, seconds, and milliseconds -->

Times:
<time datetime="08:00">  <!-- means 8am -->
<time datetime="08:00-03:00">  <!-- means 8am in Rio de Janeiro (UTC-3 hours)  -->
<time datetime="08:00+03:00">  <!-- means 8am in Madagascar (UTC+3 hours)  -->

Durations:
<time datetime="P2D">  <!-- means a duration of 2 days -->
<time datetime="PT15H10M">  <!-- means a duration of 15 hours and 10 minutes -->
```

The datetime attribute of the `<time>` element is used to display the machine-readable date time.

Following is the syntax: `<time datetime="YYYY-MM-DDThh:mm:ssTZD">`

- **YYYY** - year
- **MM** - month
- **DD** - day of the month
- **hh** - hour
- **mm** - minutes
- **ss** - seconds
- **TZD** - Time Zone Designator

You can also set PTDHMS:

- **P** - prefix for "Period"
- **D** - prefix for "Days"
- **H** - prefix for "Hours"
- **M** - prefix for "Minutes"
- **S** - prefix for "Seconds"

## HTML `<abbr>` title Attribute

The title attribute specifies extra information about an element.

The information is most often shown as a tooltip text when the mouse moves over the element.

```html
<p><abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

The title attribute can be used on any HTML element (it will validate on any HTML element. However, it is not necessarily useful).
