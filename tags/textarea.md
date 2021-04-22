# The `<textarea>` element
Defines a multi-line text input control

- This element is useful to let the user enter a comment, as an example
- The text inside this element is by default rendered in a mono spaced font
- The size of this element can be determined by the `rows` and `cols` attributes

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<textarea>` supports all global attributes. |
| `autofocus` | Not required | Specifies that a text area should automatically get focus when the page loads |
| `cols` | Any number | Specifies the visible width of a text area |
| `dirname` | textareaname.dir | Specifies that the text direction of the textarea will be submitted |
| `disabled` | Not required | Specifies that a text area should be disabled |
| `form` | Any existing form id | Specifies which form the text area belongs to |
| `maxlength` | Any number | Specifies the maximum number of characters allowed in the text area |
| `name` | Any string | Specifies a name for a text area |
| `placeholder` | Any string | Specifies a short hint that describes the expected value of a text area |
| `readonly` | Not required | Specifies that a text area should be read-only |
| `required` | Not required | Specifies that a text area is required/must be filled out |
| `rows` | Any number | Specifies the visible number of lines in a text area |
| `wrap` | `"hard"`, `"soft"` | Specifies how the text in a text area is to be wrapped when submitted in a form |

## Example
```html
<textarea id="comments_section" name="comments_section" rows="4" cols="50">
</textarea>
```