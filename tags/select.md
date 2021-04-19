# The `<select>` element
Defines a selectable drop-down list

- It can only contain [`<option>`](option.md) or [`<optgroup>`](optgroup.md) elements

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<select>` supports all global attributes. |
| `autofocus` | Not required | Specifies that the drop-down list should automatically get focus when the page loads |
| `disabled` | Not required | Specifies that a drop-down list should be disabled |
| `form` | Any existing form id | Defines which form the drop-down list belongs to |
| `multiple` | Not required | Specifies that multiple options can be selected at once |
| `name` | Any string | Defines a name for the drop-down list |
| `required` | Not required | Specifies that the user is required to select a value before submitting the form |
| `size` | Any positive integer number | Defines the number of visible options in a drop-down list |

## Example
```html
<!-- Inside a form element -->
<Select>
    <!-- Any number of option or optgroup elements -->
</select>
```