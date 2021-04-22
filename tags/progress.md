# The `<progress>` element
This element represents the completion progress of a task

- Differs from [`<meter>`](meter.md) because this element was thought to be dynamic
- You must use JavaScript to change the value of this elmeent to make it show in real time the progress of the task

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<progress>` supports all global attributes. |
| max | Any number | Specifies how much work the task requires in total. Default value is 1 |
| value | Any number | Specifies how much of the task has been completed |

## Example
```html
<progress id="file" value="32" max="100"> Downloaded 32 out of 100 MB </progress>
```