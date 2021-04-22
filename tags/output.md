# The `<output>` element
Defines a result for a process involving one or several inputs in a form

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<output>` supports all global attributes. |
| `for` | Any number of existing input id | Specifies the relationship between the result of the calculation, and the elements used in the calculation |
| `form` | Any existing form id | Specifies which form the output element belongs to |
| `name` | Any string | Specifies a name for the output element |

## Example
```html
<!-- A form opening tag with id wrapp -->
    <!-- A text input with id one -->
    <!-- A text input with id two -->
    <output for="one two" form="wrapp" value="My output"></output>
<!-- The correspondant form closing tag -->
```