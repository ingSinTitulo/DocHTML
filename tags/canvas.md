# The `<canvas>` element
Defines a container for drawing graphics with JavaScript

- This element is rendered as transparent
- This element only defines the container, not the graphics inside
- The text inside this element will be displayed if the browser does not support the `<canvas>` element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<svg>` supports all global attributes. |
| height | Height in pixels | Specifies the height of the canvas. Default value is 150 |
| width | Width in pixels | Specifies the width of the canvas Default value is 300 |

## Example
```html
<canvas id="myCanvas">
Your browser does not support the canvas tag.
</canvas>
```