# The `<area>` element
Defines an area in an image map

- This element can only be a child of a `<map>` element
- This element only requires the opening tag

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<area>` supports all global attributes. |
| `alt` | text | Specifies an alternate text for the area. Required if the href attribute is present |
| `coords` | coordinates | Specifies the coordinates of the area |
| `download` | filename | Specifies that the target will be downloaded when a user clicks on the hyperlink |
| `href` | URL | Specifies the hyperlink target for the area |
| `hreflang` | language_code | Specifies the language of the target URL |
| `media` | media query | Specifies what media/device the target URL is optimized for |
| `referrerpolicy` | `"no-referrer"`, `"no-referrer-when-downgrade"`, `"origin"`, `"origin-when-cross-origin"`, `"same-origin"`, `"strict-origin-when-cross-origin"`, `"unsafe-url"` | Specifies which referrer information to send with the link |
| `rel` | `"alternate"`, `"author"`, `"bookmark"`, `"help"`, `"license"`, `"next"`, `"nofollow"`, `"noreferrer"`, `"prefetch"`, `"prev"`, `"search"`, `"tag"` | Specifies the relationship between the current document and the target URL |
| `shape` | `"default"`, `"rect"`, `"circle"`, `"poly"` | Specifies the shape of the area |
| `target` | `"_blank"`, `"_parent"`, `"_self"`, `"_top"`, any name of an existing frame | Specifies where to open the target URL |
| `type` | Any valid MIME string | Specifies the media type of the target URL |

## Example
```html
<!-- An im element that has the attribute usemap with the value #myphoto -->
<!-- A map opening tag with the name myphoto -->
    <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
    <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
<!-- The correspondant map closing tag -->
```