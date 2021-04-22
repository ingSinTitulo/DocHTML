# The `<video>` element
Defines an embeded video stream

- The inner text of this element will be only visible when the browser does not support the `<video>` element
- The three main formats to be used as an audio source are MP4, WebM and OGG

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<video>` supports all global attributes. |
| `autoplay` | Not required | Specifies that the audio will start playing as soon as it is ready |
| `controls` | Not required | Specifies that audio controls should be displayed (such as a play/pause button etc) |
| `height` | Height in pixels | Sets the height of the video player |
| `loop` | Not required | Specifies that the audio will start over again, every time it is finished |
| `muted` | Not required | Specifies that the audio output should be muted |
| `poster` | Any valid URL | Specifies an image to be shown while the video is downloading, or until the user hits the play button |
| `preload` | `"auto"`, `"metadata"`, `"none"` | Specifies if and how the author thinks the audio should be loaded when the page loads |
| `src` | Any valid URL | Specifies the URL of the audio file |
| `width` | Width in pixels | Sets the width of the video player |

## Example
```html
<video width="320" height="240" controls src="video.mp4">Your browser does not support the video element</video>
```