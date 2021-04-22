# The `<datalist>` element
Defines a list of pre-defined options for a text [`<input>`](input.md) element

- This element defines an autocomplete feature for text [`<input>`](input.md) elements
- User will see a drop-down list of pre-defined options as they type
- The id of this element must have the same value as the `list` attribute of the [`<input>`](input.md) element to bind them together
- This element can only contain [`<optgroup>`](optgroup.md) or [`<option>`](option.md) elements

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<datalist>` supports all global attributes. |

## Example
```html
<!-- here goes a text input with the attribute list with value myautocomplete -->
<datalist id="myautocomplete">
    <!-- List of options -->
</datalist>
```