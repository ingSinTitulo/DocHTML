# The `<embed>` element
Defines embedded content

- For embeding images, other documents, audio and video there are better options than this element
- Java applets and plug-ins, ActiveX controls and Flash are no longer supported and should not be used in this element
- There is not really an incentive to use this element, but it is not marked as deprecated yet, so here it is
- This element only required the opening tag

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<embed>` supports all global attributes. |
| `height` | Height in pixels | Specifies the height of the embedded content |
| `src` | Any valid URL | Specifies the address of the external file to embed |
| `type` | Any MIME type | Specifies the media type of the embedded content |
| `width` | Width in pixels | Specifies the width of the embedded content |

## Example
```html
<embed type="image/jpg" src="mydog.jpg" width="300" height="200">
```