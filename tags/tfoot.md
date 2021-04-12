# The `<tfoot>` element
Defines a table footer group

- Must be sibling of [`<thead>`](thead.md) and [`<tbody>`](tbody.md) elements
- Browsers use this element to define the footer of a table, and keeps it static while the [`<tbody>`](tbody.md) may scroll normally
- Can only have [`<tr>`](tr.md) elements inside
- Can only be a direct child of the [`<table>`](table.md) element
- Must be used after any [`<caption>`](caption.md), [`<colgroup>`](colgroup.md), [`<thead>`](thead.md) or [`<tbody>`](tbody.md) elements

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<tfoot>` supports all global attributes. |

## Example
```html
<!-- Table opening tag -->
    <!-- A <thead> element -->
    <!-- A <tbody> element -->
    <tfoot>
        <!-- One or more <tr> elements -->
    </tfoot>
<!-- Table closing tag -->
```