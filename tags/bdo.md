# The `<bdo>` element
Defines a text direction override

- Useful to insert text in a language that is written in a different direction than the document
- This element will always override the text direction without any validation, even if the text should not switch its direction, so be careful

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<bdo>` supports all global attributes. |
| `dir` | `"ltr"`, `"rtl"` | Required. Specifies the text direction of the text inside the `<bdo>` element |

## Example
```html
Cuidado, caliente.

Danger, hot.

<bdo dir="rtl">
مراقب باشید این سطح گرم است
</bdo>
```