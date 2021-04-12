# The `<tr>` element
Defines a row in a table

- It can only be child of a [`<thead>`](thead.md), [`<tbody>`](tbody.md) or [`<tfoot>`](tfoot.md) elements
- If inside a [`<thead>`](thead.md), it can only contain [`<th>`](th.md) elements
- If inside [`<tbody>`](tbody.md) or [`<tfoot>`](tfoot.md), it can only contain [`<td>`](td.md) elements

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<tr>` supports all global attributes. |

## Example
```html
<!-- Table opening tag -->
    <!-- A <thead>, <tbody> or <tfoot> opening tag -->
        <tr>
            <!-- If inside <thead>, here goes only <th> elements -->
            <!-- If inside <tbody> or <tfoot>, here goes only <td> elements -->
        </tr>
    <!-- The correspondant <thead>, <tbody> or <tfoot> closing tag -->
<!-- Table closing tag -->
```