# The `<col>` element
Defines properties for a column in a table

- This element specifies column properties for each column within a [`<colgroup>`](colgroup.md) element
- Useful for applying styles to entire columns, instead of repeating the styles for each cell, for each row

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<col>` supports all global attributes. |
| span | Any valid unsigned integer number | Specifies the number of columns a `<col>` element should span |

## Example
```html
<!-- Table opening tag -->
    <!-- A possible table caption element -->
    <!-- A <colgroup> opening tag -->
        <col span="2" class="yellow">
        <col class="red">
    <!-- The correspondant <colgroup> closing tag -->
    <!-- The three main table groups -->
<!-- Table closing tag -->
```