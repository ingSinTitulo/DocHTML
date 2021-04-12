# The `<tbody>` element
Defines a table body group

- Must be sibling of [`<thead>`](thead.md) and [`<tfoot>`](tfoot.md) elements
- Browsers use this elment to make the scroll independent from [`<thead>`](thead.md) and `<tbody>` to make the `<tbody>` the only scrollable element in the table
- Can only have [`<tr>`](tr.md) elements inside
- Can only be a direct child of the [`<table>`](table.md) element
- Must be used after any [`<caption>`](caption.md), [`<colgroup>`](colgroup.md) or [`<thead>`](thead.md) elements

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<tbody>` supports all global attributes. |

## Example
```html
<!-- Table opening tag -->
    <!-- A <thead> element -->
    <tbody>
        <!-- One or more <tr> elements -->
    </tbody>
<!-- Table closing tag -->
```