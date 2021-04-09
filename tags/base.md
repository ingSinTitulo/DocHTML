# The `<base>` element
Defines the base url of all relative URLs in the document. When linking a CSS or a JavaScript file to the document, if the url of the source is `assets/index.js`, and the `href` element of the base element is `/myfiles/`, the file will be loaded from `/myfiles/assets/index.js`.

- This element only needs the opening tag

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<base>` supports all global attributes. |
| href | Any valid URL | Specifies the base URL for all relative URLs in the page |
| target | `"_blank"`, `"_parent"`, `"_self"`, `"_top"` | Specifies the default target for all hyperlinks and forms in the page |

## Example
```html
<!-- This line means: All paths are relative to the assets folder and all will be opnened in a new tab -->
<base href="/assets/" target="_blank">
```