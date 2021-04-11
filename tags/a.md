# The `<a>` element
Defines a hyperlink

- Hyperlinks are the way that HTML documents connect and refer to each other
- The most common and most important attribute in this element is `href`, which indicates its destination
- When a user clicks an `<a>` element, the browser will open the destination address

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<a>` supports all global attributes. |
| download | A valid filename of an existing and publicly available file in server | Specifies that the target will be downloaded when a user clicks on the hyperlink |
| href | Any valid URL | Specifies the URL of the page the link goes to |
| hreflang | Any [ISO 639-1](https://www.loc.gov/standards/iso639-2/php/code_list.php) complaint language string | Specifies the language of the linked document |
| media | Any valid media query | Specifies what media/device the linked document is optimized for |
| ping | Any valid URL | Specifies a space-separated list of URLs to which, when the link is followed, post requests with the body ping will be sent by the browser (in the background). Typically used for tracking. |
| referrerpolicy | `"no-referrer"`, `"no-referrer-when-downgrade"`, `"origin"`, `"origin-when-cross-origin"`, `"same-origin"`, `"strict-origin-when-cross-origin"`, `"unsafe-url"` | Specifies which referrer information to send with the link |
| rel | `"alternate"`, `"author"`, `"bookmark"`, `"external"`, `"help"`, `"license"`, `"next"`, `"nofollow"`, `"noreferrer"`, `"noopener"`, `"prev"`, `"search"`, `"tag"` | Specifies the relationship between the current document and the linked document |
| target | `"_blank"`, `"_parent"`, `"_self"`, `"_top"` | Specifies where to open the linked document |
| type | Any valid MIME type string | Specifies the media type of the linked document |

## Example
```html
<!-- by default, this link will be opened in the same window -->
<a href="/contact" rel="help">Contact me for support</a>
```