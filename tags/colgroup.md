# The `<colgroup>` element
Defines a column group in a table

- Can only be child of a [`<table>`](table.md) element
- Can only be after the [`<caption>`](caption.md) element
- Can only be before any [`<thead>`](thead.md), [`<tbody>`](tbody.md), [`<tfoot>`](tfoot.md), or [`<tr>`](tr.md) element
- Can only have [`<col>`](col.md) elements as children

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<colgroup>` supports all global attributes. |

## Example
```html
<!-- Table opening tag -->
    <!-- A possible table caption element -->
    <colgroup>
        <!-- A list of <col> elements -->
    </colgroup>
    <!-- The three main table groups -->
<!-- Table closing tag -->
```