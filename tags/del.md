# The `<del>` element
Defines text that has been retired from the document

- Usually rendered as text with a line through it
- This element is a counter part of the [`<ins>`](ins.md) element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<s>` supports all global attributes. |
| `cite` | Any valid URL | Specifies a URL to a document that explains the reason why the text was deleted/changed |
| `datetime` | Any date time string matching YYYY-MM-DDThh:mm:ssTZD | Specifies the date and time of when the text was deleted/changed |

## Example
```html
The planets in the solar system are Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune <del>and Pluto</del>
```