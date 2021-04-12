# The `<ins>` element
Defines text that has inserted in the document

- Usually rendered as underlines text
- This element is a counter part of the [`<del>`](del.md) element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<s>` supports all global attributes. |
| `cite` | Any valid URL | Specifies a URL to a document that explains the reason why the text was inserted/changed |
| `datetime` | Any date time string matching YYYY-MM-DDThh:mm:ssTZD | Specifies the date and time of when the text was inserted/changed |

# Example
```html
The atom core is conformed by protons and neutrons. <ins>Which themselves are conformed by quarks.</ins>
```