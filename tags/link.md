# The `<link>` element
Defines the relantionship between the document and external resources.

- Commonly used to link CSS stylesheets and favicons.
- This element only needs the opening tag

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<html>` supports all global attributes. |
| crossorigin | `"anonymous"`, `"use-credentials"` | Specifies how the element handles cross-origin requests |
| href | Any valid URL | Specifies the location of the linked document |
| hreflang | Any [ISO 639-1](https://www.loc.gov/standards/iso639-2/php/code_list.php) complaint language string | Specifies the language of the text in the linked document |
| media | Any valid media query | Specifies on what device the linked document will be displayed |
| referrerpolicy | `"no-referrer"`, `"no-referrer-when-downgrade"`, `"origin"`, `"origin-when-cross-origin"`, `"unsafe-url"` | Specifies which referrer to use when fetching the resource |
| rel | `"alternate"`, `"author"`, `"dns-prefetch"`, `"help"`, `"icon"`, `"license"`, `"next"`, `"pingback"`, `"preconnect"`, `"prefetch"`, `"preload"`, `"prerender"`, `"prev"`, `"search"`, `"stylesheet"` | **Required**. Specifies the relationship between the current document and the linked document |
| sizes | `"[Height as number in pixels]x[Width as number in pixels]"`, `"any"` | Specifies the size of the linked resource. Only for rel="icon" |
| title | Any string | Defines a preferred or an alternate stylesheet |
| type | Any valid media type | Specifies the media type of the linked document |

## Example
```html
<!-- This will link a stylesheet to our document -->
<link rel="stylesheet" href="/assets/css/index.css">

<!-- This will show the favicon of our page when it is requested in a resolution of 16 pixels width by 16 pixels height -->
<link rel="icon" type="image/png" href="imagen_16.png" sizes="16x16">

<!-- This one in 32 by 32 -->
<link rel="icon" type="image/png" href="imagen_32.png" sizes="32x32">

<!-- And this one on 64 by 64 -->
<link rel="icon" type="image/png" href="imagen_64.png" sizes="64x64">

<!-- This will show our favicon in any resolution as it is a scalable vector graphics format icon -->
<link rel="icon" type="image/svg+xml" href="imagen.svg" sizes="any">
```