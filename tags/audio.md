# The `<audio>` element
Defines an embeded sound stream

- The inner text of this element will be only visible when the browser does not support the `<audio>` element
- The three main formats to be used as an audio source are MP3, WAV and OGG

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<audio>` supports all global attributes. |
| `autoplay` | Not required | Specifies that the audio will start playing as soon as it is ready |
| `controls` | Not required | Specifies that audio controls should be displayed (such as a play/pause button etc) |
| `loop` | Not required | Specifies that the audio will start over again, every time it is finished |
| `muted` | Not required | Specifies that the audio output should be muted |
| `preload` | `"auto"`, `"metadata"`, `"none"` | Specifies if and how the author thinks the audio should be loaded when the page loads |
| `src` | Any valid URL | Specifies the URL of the audio file |

## Example
```html
<audio controls autoplay src="audio.mp3">Your browser does not support the audio element</audio>
```