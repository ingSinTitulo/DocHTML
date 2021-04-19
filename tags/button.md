# The `<button>` element
Defines a clickable button

- This element differs form `<input type="submit">` because in this element you can add HTML structure
- You must always specify the `type` attribute in this element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<button>` supports all global attributes. |
| `autofocus` | Not required | Specifies that a button should automatically get focus when the page loads |
| `disabled` | Not required | Specifies that a button should be disabled |
| `form` | An existing form id | Specifies which form the button belongs to |
| `formaction` | Any valid URL | Specifies where to send the form-data when a form is submitted. Only for `type="submit"` |
| `formenctype` | `"application/x-www-form-urlencoded"`, `"multipart/form-data"`, `"text/plain"` | Specifies how form-data should be encoded before sending it to a server. Only for `type="submit"` |
| `formmethod` | `"get"`, `"post"` | Specifies how to send the form-data (which HTTP method to use). Only for `type="submit"` |
| `formnovalidate` | Not required | Specifies that the form-data should not be validated on submission. Only for `type="submit"` |
| `formtarget` | `"_blank"`, `"_self"`, `"_parent"`, `"_top"`, and existing framename | Specifies where to display the response after submitting the form. Only for `type="submit"` |
| `name` | Any string | Specifies a name for the button |
| `type` | `"button"`, `"reset"`, `"submit"` | Specifies the type of button |
| `value` | Any string | Specifies an initial value for the button |

## Example
```html
<!-- Usually, this will be inside a form, after the input fields -->
<button type="button">Save</button>
```