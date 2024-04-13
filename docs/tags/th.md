# HTML `<th>` Tag

The `<th>` tag defines a header cell in an HTML table.

An HTML table has two kinds of cells:

- Header cells - contains header information (created with the `<th>` element)
- Data cells - contains data (created with the `<td>` element)

The text in `<th>` elements are bold and centered by default.

The text in `<td>` elements are regular and left-aligned by default.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>The table element</title>
    <style>
    table, th, td {
      border: 1px solid black;
    }
    </style>
  </head>
  <body>
  <h1>The table element</h1>
  <table>
    <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
    <tr>
      <td>January</td>
      <td>$100</td>
    </tr>
    <tr>
      <td>February</td>
      <td>$80</td>
    </tr>
  </table>
  </body>
</html>
```
