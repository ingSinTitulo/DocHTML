# The `<optgroup>` element
Defines a group of options

- Must be always inside a [`<select>`](select.md) or a [`<datalist>`](datalist.md) element
- If inside a [`<select>`](select.md) element, it will show a label as a header for the group
- If inside a [`<datalist>`](datalist.md) it will be rendered without any special style and without label header, as if the options would not be inside an `<optgroup>`

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<optgroup>` supports all global attributes. |
| `disabled` | Not required | Specifies that an option-group should be disabled |
| `label` | Any string | Specifies a label for an option-group |

## Example
```html
<!-- A select opening tag -->
    <optgroup label="Group name"> <!-- This will be rendered as the header of the group -->
        <!-- A group of options -->
    </optgroup>
<!-- A select closing tag -->
```