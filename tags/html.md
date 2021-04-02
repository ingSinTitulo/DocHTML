# The `<html>` element
The root of the HTML document

- There must be only one html element in each document.
- This element works as the parent of [`<head>`](head.md) and [`<body>`](body.md) elements.
- It is not allowed to have parent element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<html>` supports all global attributes. |
| `lang` | Any [ISO 639-1](https://www.loc.gov/standards/iso639-2/php/code_list.php) complaint language string | We must always include this attribute for SEO. |

## Example
```html
<html lang="en">
    <!-- here goes the head element, and can only be one head element -->
    <!-- here goes the body element, and can only be one body element -->
    <!-- nothing else can be at this level, only head and body elements and comments are allowed here -->
</html>
```