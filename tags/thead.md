# The `<thead>` element
Defines a table header group

- Must be sibling of [`<tbody>`](tbody.md) and [`<tfoot>`](tfoot.md) elements
- Browsers use this element to define the header of a table, and keeps it static while the [`<tbody>`](tbody.md) may scroll normally
- Can only have [`<tr>`](tr.md) elements inside
- Can only be a direct child of the [`<table>`](table.md) element
- Must be used after any [`<caption>`](caption.md) or [`<colgroup>`](colgroup.md) elements
- Must be before any [`<tbody>`](tbody.md), [`<tfoot>`](tfoot.md) and [`<tr>`](tr.md) elements

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<thead>` supports all global attributes. |

## Example
```html
<!-- Table opening tag -->
    <thead>
        <!-- One or more <tr> elements -->
    </thead>
<!-- Table closing tag -->
```