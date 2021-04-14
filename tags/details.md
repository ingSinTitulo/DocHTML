# The `<details>` element
Defines additional details that the user can open and close on demand

- This element creates an interactive widget that the user can open and close
- This element is rendered as a block with the word "Details" and an arrow to indicate if it is open or closed.
- When the user clicks this element, the additional details are displayed, and if it is clicked again, the details will hide

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<details>` supports all global attributes. |
| `open` | Not required | If present, it specifies that the details should be visible (open) to the user |

## Example
```html
I like enchiladas at any time
<details>
Green enchiladas only
</details>
```