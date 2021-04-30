# The `<img>` element
Defines an embedded image

- This element only requires the opening tag

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<img>` supports all global attributes. |
| `alt` | Any string | **Required**. Specifies an alternate text for an image
| `crossorigin` | `"anonymous"`, `"use-credentials"` | Allow images from third-party sites that allow cross-origin access to be used with canvas |
| `height` | Height in pixels | Specifies the height of an image |
| `ismap` | Not required | Specifies an image as a server-side image map |
| `loading` | `"eager"`, `"lazy"` | Specifies whether a browser should load an image immediately or to defer loading of images until some conditions are met |
| `longdesc` | Any valid URL | Specifies a URL to a detailed description of an image |
| `referrerpolicy` | `"no-referrer"`, `"no-referrer-when-downgrade"`, `"origin"`, `"origin-when-cross-origin"`, `"unsafe-url"` | Specifies which referrer information to use when fetching an image |
| `sizes` | A set with any number sizes | Specifies image sizes for different page layouts |
| `src` | Any valid URL | **Required**. Specifies the path to the image |
| `srcset` | A list with any number of valid URLs | Specifies a list of image files to use in different situations |
| `usemap` | #[Any name for an `<imagemap>`] | Specifies an image as a client-side image map |
| `width` | Width in pixels | Specifies the width of an image |

## Example
```html
<img src="mydog.jpg" alt="My dog with a stick">
```