# The `<li>` element
Defines an ordered or unordered list

- This element can only be children of [`<ul>`](ul.md) or [`<ol>`](ol.md)
- If inside [`<ul>`](ul.md), this element will be rendered with a bullet
- If inside [`<ol>`](ol.md), this element will be rendered depending on the configuration of the [`<ol>`](ol.md) list, with numbers or letters

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<li>` supports all global attributes. |
| value | Any valid unsigned integer number | Only for [`<ol>`](ol.md) lists. Specifies the start value of a list item. The following list items will increment from that number |

## Example
```html
<!-- Here goes an <ul> or <ol> opening tag -->
    <li>Chicken</li>
    <li>Beef</li>
    <li>Shrimp</li>
<!-- Here goes the correspondant <ul> or <ol> closing tag -->
```