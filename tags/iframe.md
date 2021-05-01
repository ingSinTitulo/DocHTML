# The `<iframe>` element
Defines an inline embedded document inside the current document

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<iframe>` supports all global attributes. |
| `allow` | ... | Specifies a feature policy for the `<iframe>` |
| `allowfullscreen` | `"true"`, `"false"` | Set to true if the `<iframe>` can activate fullscreen mode by calling the requestFullscreen() method |
| `allowpaymentrequest` | `"true"`, `"false"` | Set to true if a cross-origin `<iframe>` should be allowed to invoke the Payment Request API |
| `height` | Height in pixels | Specifies the height of an `<iframe>`. Default height is 150 pixels |
| `loading` | `"eager"`, `"lazy"` | Specifies whether a browser should load an iframe immediately or to defer loading of iframes until some conditions are met |
| `name` | Any string | Specifies the name of an `<iframe>` |
| `referrerpolicy` | `"no-referrer"`, `"no-referrer-when-downgrade"`, `"origin"`, `"origin-when-cross-origin"`, `"same-origin"`, `"strict-origin-when-cross-origin"`, `"unsafe-url"` | Specifies which referrer information to send when fetching the iframe |
| `sandbox` | `"allow-forms"`, `"allow-pointer-lock"`, `"allow-popups"`, `"allow-same-origin"`, `"allow-scripts"`, `"allow-top-navigation"` | Enables an extra set of restrictions for the content in an `<iframe>` |
| `src` | Any valid URL | Specifies the address of the document to embed in the `<iframe>` |
| `srcdoc` | Valid HTML code | Specifies the HTML content of the page to show in the `<iframe>` |
| `width` | Width in pixels | Specifies the width of an `<iframe>`. Default width is 300 pixels |

## Example
```html
<iframe src="https://www.google.com" title="My google search without an API key :)"></iframe>
```