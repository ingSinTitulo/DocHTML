# The `<option>` element
Defines an option in a selectable drop-down list

- Must always be inside a [`<select>`](select.md), [`<optgroup>`](optgroup.md) or [`<datalist>`](datalist.md)
- To set a value for the [`<select>`](select.md) or the [`<input>`](input.md) (trough the [`<datalist>`](datalist.md) element), you must specify the `value` attribute in this element
- If no `value` specified, the value will be the inner text of this element and this is completely valid and acceptable

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<option>` supports all global attributes. |
| `disabled` | Not required | Specifies that an option should be disabled |
| `label` | Any string | Specifies a shorter label for an option |
| `selected` | Not required | Specifies that an option should be pre-selected when the page loads |
| `value` | Any string | Specifies the value to be sent to a server |

## Example
```html
<!-- A select opening tag -->
    <option>One</option> <!-- If this element is selected, the select element will have the inner text as its value, in this case it would be the string one -->
    <option value="two">2</option> <!-- If this element is selected, the select element will have the value attribute as its value, in this case the string two -->
<!-- A select closing tag -->
```