# HTML `<table>` Tag

The `<table>` tag defines an HTML table.

An HTML table consists of one `<table>` element and one or more `<tr>`, `<th>`, and `<td>` elements.

The `<tr>` element defines a table row, the `<th>` element defines a table header, and the `<td>` element defines a table cell.

An HTML table may also include `<caption>`, `<colgroup>`, `<thead>`, `<tfoot>`, and `<tbody>` elements.

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
