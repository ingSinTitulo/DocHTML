# The `<form>` element
Defines a form for user input

- This element is the parent for the following elements:
    - [`<input>`](input.md)
    - [`<textarea>`](textarea.md)
    - [`<button>`](button.md)
    - [`<select>`](select.md)
    - [`<option>`](option.md)
    - [`<optgroup>`](optgroup.md)
    - [`<fieldset>`](fieldset.md)
    - [`<label>`](label.md)
    - [`<output>`](output.md)
- All the elements inside this that will be added to the form payload, must have the `name` attribute

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<form>` supports all global attributes. |
| `accept-charset` | Any valid charset string | Specifies the character encodings that are to be used for the form submission |
| `action` | Any valid URL | Specifies where to send the form-data when a form is submitted |
| `autocomplete` | `"on"`, `"off"` | Specifies whether a form should have autocomplete on or off |
| `enctype` | `"application/x-www-form-urlencoded"`, `"multipart/form-data"`, `"text/plain"` | Specifies how the form-data should be encoded when submitting it to the server (only for `method="post"`) |
| `method` | `"get"`, `"post"` | Specifies the HTTP method to use when sending form-data |
| `name` | Any valid string for a variable name | Specifies the name of a form |
| `novalidate` | Not required | Specifies that the form should not be validated when submitted |
| `rel` | `"external"`, `"help"`, `"license"`, `"next"`, `"nofollow"`, `"noopener"`, `"noreferrer"`, `"opener"`, `"prev"`, `"search"` | Specifies the relationship between a linked resource and the current document |
| `target` | `"_blank"`, `"_self"`, `"_parent"`, `"_top"` | Specifies where to display the response that is received after submitting the form |

## Example
```html
<form action="/backend.php" method="post">
    <!-- Any number of valid form children -->
</form>
```