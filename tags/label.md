# The `<label>` element
Defines a label for other elements

- The elements that can have a label are:
    - [`<input type="checkbox">`](input.md)
    - [`<input type="color">`](input.md)
    - [`<input type="date">`](input.md)
    - [`<input type="datetime-local">`](input.md)
    - [`<input type="email">`](input.md)
    - [`<input type="file">`](input.md)
    - [`<input type="month">`](input.md)
    - [`<input type="number">`](input.md)
    - [`<input type="password">`](input.md)
    - [`<input type="radio">`](input.md)
    - [`<input type="range">`](input.md)
    - [`<input type="search">`](input.md)
    - [`<input type="tel">`](input.md)
    - [`<input type="text">`](input.md)
    - [`<input type="time">`](input.md)
    - [`<input type="url">`](input.md)
    - [`<input type="week">`](input.md)
    - [`<meter>`](meter.md)
    - [`<progress>`](progress.md)
    - [`<select>`](select.md)
    - [`<textarea>`](textarea.md)
- Screen reader use this element to read a description when user focuses it
- Clicking this element has the same effect as clicking the element this is a label for

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<label>` supports all global attributes. |
| `for` | Any existing input, textarea, meter, progress or select element id | Specifies the id of the form element the label should be bound to |
| `form` | Any existing form id | Specifies which form the label belongs to |

## Example
```html
<label for="name">What is your name?</label>
<!-- Here goes a text input field with the id name -->
```