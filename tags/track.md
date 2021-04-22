# The `<track>` element
Defines a text track for an [`<audio>`](audio.md) or [`<video>`](video.md) element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<track>` supports all global attributes. |
| `default` | Not required | Specifies that the track is to be enabled if the user's preferences do not indicate that another track would be more appropriate |
| `kind` | `"captions"`, `"chapters"`, `"descriptions"`, `"metadata"`, `"subtitles"` | Specifies the kind of text track |
| `label` | Any string | Specifies the title of the text track |
| `src` | Any valid URL | Required. Specifies the URL of the track file |
| `srclang` | Any [ISO 639-1](https://www.loc.gov/standards/iso639-2/php/code_list.php) complaint language string | Specifies the language of the track text data (required if kind="subtitles") |

## Example
```html
<!-- An audio, video or picture opening tag -->
    <!-- Any number of source elements -->
    <track src="fgsubtitles_en.vtt" kind="subtitles" srclang="en" label="English">
    <track src="fgsubtitles_no.vtt" kind="subtitles" srclang="no" label="Norwegian">
<!-- The correspondant audio, video or picture closing tag -->
```