# The `<source>` element
Defines an option of stream source for an [`<audio>`](audio.md) or [`<video>`](video.md) element

- Useful to let the browser choose from the options, as the first compatible media will be played and the others will be skipped

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<source>` supports all global attributes. |
| `media` | Any valid media query definition | Accepts any valid media query that would normally be defined in a CSS |
| `src` | Any valid URL | Required when `<source>` is used in [`<audio>`](audio.md) and [`<video>`](video.md). Specifies the URL of the media file |
| `srcset` | Any valid URL | Required when `<source>` is used in [`<picture>`](picture.md). Specifies the URL of the image to use in different situations |
| `type` | MIME-type | Specifies the MIME-type of the resource |

## Example
```html
<!-- An audio, video or picture opening tag -->
    <source src="abc.mp4" type="video/mpeg">
    <source src="abc.ogg" type="video/ogg">
<!-- The correspondant audio, video or picture closing tag -->
```