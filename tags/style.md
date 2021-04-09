# The `<style>` element
Used to include CSS code within the documents instead of linking an external file. **Avoid using this element**, you must always separate your css code from the HTML document.

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<style>` supports all global attributes. |
| `media` | Any media query | Specifies what media/device the media resource is optimized for |
| `type` | "text/css" | Specifies the media type of the `<style>` tag |

## Example
```html
<style>
    /* Everithing inside this element is treated as CSS code */
    /* Even notice that this line is a CSS-styled comment, not a comment tag */
</style>
```