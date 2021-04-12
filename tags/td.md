# The `<td>` element
Deines a data cell within a table body group row or footer group row

- This element can only be inside a [`<tr>`](tr.md) element which itself is inside a [`<tbody>`](tbody.md) or [`<tfoot>`](tfoot.md) element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<td>` supports all global attributes. |

## Example
```html
<!-- Table opening tag -->
    <!-- A <tbody> or <tfoot> opening tag -->
        <!-- A table row opening tag -->
            <td>John Smith</td>
            <td>708 Coconut st.</td>
            <td>24</td>
            <td>7' 3"</td>
        <!-- A table row closing tag -->
    <!-- The correspondant <tbody> or <tfoot> closing tag -->
<!-- Table closing tag -->
```