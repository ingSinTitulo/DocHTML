# The `<wbr>` element
Defines a possible word break. The line will only be sliced if the resolution is less than the text in each side of the `<wbr>` element.

- This element only requires the opening tag
- Useful to define the correct work break opportunities in your text

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<wbr>` supports all global attributes. |

## Example
```html
<!-- If the width of the window is smaller than the width of the following line, the renderer will slice the line where is the <wbr> element -->
Phasellus ut fermentum mi.<wbr>Suspendisse eget est augue.
```