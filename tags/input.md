# The `<input>` element
Defines an input where the user can input data

- One of the most complex elements in HTML
- The most important child of [`<form>`](form.md) element
- It is rendered differently depending on the type specified
- If not specified, the default input type is text

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<input>` supports all global attributes. |
| `accept` | Any valid and existing file extension (i.e. `".xml"`), `"audio/*"`, `"video/*"`, `"image/*"`, Any valid [IANA media type](http://www.iana.org/assignments/media-types/media-types.xhtml) | Specifies a filter for what file types the user can pick from the file input dialog box (only for type="file") |
| `alt` | Any string | Specifies an alternate text for images (only for `type="image"`) |
| `autocomplete` | `"on"`, `"off"` | Specifies whether an `<input>` element should have autocomplete enabled |
| `autofocus` | Not required | Specifies that an `<input>` element should automatically get focus when the page loads |
| `checked` | Not required | Specifies that an `<input>` element should be pre-selected when the page loads (for `type="checkbox"` or `type="radio"`) |
| `dirname` | `"inputname.dir"` | Specifies that the text direction will be submitted |
| `disabled` | Not required | Specifies that an `<input>` element should be disabled |
| `form` | An existing form id | Specifies the form the `<input>` element belongs to |
| `formaction` | Any valid URL | Specifies the URL of the file that will process the input control when the form is submitted (for `type="submit"` and `type="image"`) |
| `formenctype` | `"application/x-www-form-urlencoded"`, `"multipart/form-data"`, `"text/plain"` | Specifies how the form-data should be encoded when submitting it to the server (for `type="submit"` and `type="image"`) |
| `formmethod` | `"get"`, `"post"` | Defines the HTTP method for sending data to the action URL (for `type="submit"` and `type="image"`) |
| `formnovalidate` | Not required | Defines that form elements should not be validated when submitted |
| `formtarget` | `"_blank"`, `"_self"`, `"_parent"`, `"_top"`, an existing framename | Specifies where to display the response that is received after submitting the form (for `type="submit"` and `type="image"`) |
| `height` | Any valid size in pixels | Specifies the height of an `<input>` element (only for `type="image"`) |
| `list` | Any existing datalist id | Refers to a [`<datalist>`](datalist.md) element that contains pre-defined options for an `<input>` element |
| `max` | Any number, any valic date string | Specifies the maximum value for an `<input>` element |
| `maxlength` | Any valid positive integer number | Specifies the maximum number of characters allowed in an `<input>` element |
| `min` | Any nmber, any valid date string | Specifies a minimum value for an `<input>` element |
| `minlength` | Any valid positive integer number | Specifies the minimum number of characters required in an `<input>` element |
| `multiple` | Not required | Specifies that a user can enter more than one value in an `<input>` element |
| `name` | Any string | Specifies the name of an `<input>` element |
| `pattern` | Any valid regular expression | Specifies a regular expression that an `<input>` element's value is checked against |
| `placeholder` | Any valid string | Specifies a short hint that describes the expected value of an `<input>` element |
| `readonly` | Not required | Specifies that an input field is read-only |
| `required` | Not required | Specifies that an input field must be filled out before submitting the form |
| `size` | Any positive integer number | Specifies the width, in characters, of an `<input>` element |
| `src` | Any valid URL | Specifies the URL of the image to use as a submit button (only for `type="image"`) |
| `step` | Any positive inetegr number, any string | Specifies the interval between legal numbers in an input field |
| `type` | `"button"`, `"checkbox"`, `"color"`, `"date"`, `"datetime-local"`, `"email"`, `"file"`, `"hidden"`, `"image"`, `"month"`, `"number"`, `"password"`, `"radio"`, `"range"`, `"reset"`, `"search"`, `"submit"`, `"tel"`, `"text"`, `"time"`, `"url"`, `"week"` | Specifies the type `<input>` element to display |
| `value` | Any string | Specifies the value of an `<input>` element | 
| `width` | Any valid size in pixels | Specifies the width of an `<input>` element (only for `type="image"`) |

## Example
```html
<!-- This must always be inside a form element -->
<input type="text" id="first_name" name="first_name">
```