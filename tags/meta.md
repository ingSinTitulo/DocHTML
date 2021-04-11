# The `<meta>` element
Used to define metadata about the document.

- This element only requires the opening tag
- This element can only be inside the head element
- Metadata defined with this element will not be displayed in the page
- Metadata is used by the broser and search engines to get extra information about the document beyond its contents
- A special meta tag is the character set definition, which you must **always** include in any document
- Another kinda special tag is the viewport, it is not mandatory, but we highly encourage you to include

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<meta>` supports all global attributes. |
| charset | Any character set definition string | Specifies the character encoding for the HTML document |
| name | `"application-name"`, `"author"`, `"description"`, `"generator"`, `"keywords"`, `"viewport"` | Specifies a name for the metadata |
| content | Any string | Specifies the value associated with the http-equiv or name attribute |
| http-equiv | `"content-security-policy"`, `"content-type"`, `"default-style"`, `"refresh"` | Not recomended, all HTTP headers must come in the response headers. Provides an HTTP header for the information/value of the content attribute |

## Example
```html
<!-- This is a special meta tag, also this is mandatory in all HTML document -->
<meta charset="UTF-8">

<!-- This is anothe more or less special tag to specify the viewport, not mandatory, but you should include it -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Defining the author od the document -->
<meta name="author" content="John Doe">

<!-- Defining the description of the document (Good for SEO) -->
<meta name="description" content="My awesome web page">

<!-- Defining the keywords for search engines (Also good for SEO) -->
<meta name="keywords" content="HTML, CSS, JavaScript">
```