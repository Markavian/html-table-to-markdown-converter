# html-table-to-markdown-converter

Converts HTML tables to Markdown. Paste table HTML in, click Convert.

## Latest release

### 1.0.0

See:
- https://cdn.rawgit.com/Markavian/html-table-to-markdown-converter/1.0.0/table-converter.html

### Example

Sample HTML input taken from Chrome `Right Click` > `Inspect`.
```html
<table>
<thead>
<tr>
  <th>Heading</th>
  <th>Verified</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Row 1</td>
  <td>Yes</td>
</tr>
<tr>
  <td>Row 2</td>
  <td>No</td>
</tr>
<tr>
  <td>Row 3</td>
  <td>Maybe</td>
</tr>
</tbody>
</table>
```

Output: 
```md
| Heading | Verified |
| --- | --- |
| Row 1 | Yes |
| Row 2 | No |
| Row 3 | Maybe |
```

Output rendered as markdown:

| Heading | Verified |
| --- | --- |
| Row 1 | Yes |
| Row 2 | No |
| Row 3 | Maybe |

## Wishlist

- Pretty format the output
- Provide option to remove the opening | for multi-column tables
