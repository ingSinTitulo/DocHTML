# The `<object>` element
Defines embedded content

- For embeding images, other documents, audio and video there are better options than this element
- Java applets and plug-ins, ActiveX controls and Flash are no longer supported and should not be used in this element
- There is not really an incentive to use this element, but it is not marked as deprecated yet, so here it is
- Wait a minute, this seems a lot like the [`<embed>`](embed.md) element...

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<object>` supports all global attributes. |
| `data` | Any valid URL | Specifies the URL of the resource to be used by the object |
| `form` | Any existing form id | Specifies which form the object belongs to |
| `height` | Height in pixels | Specifies the height of the embedded content |
| `name` | Any string | Specifies a name for the object |
| `type` | Any MIME type | Specifies the media type of the embedded content |
| `typemustmatch` | `"true"`, `"false"` | Specifies whether the type attribute and the actual content of the resource must match to be displayed |
| `usemap` | #[map id] | Specifies the name of a client-side image map to be used with the object |
| `width` | Width in pixels | Specifies the width of the embedded content |

## Example
```html
<object data="mydog.jpg" width="300" height="200"></object>
```