# The `<script>` element
Used to embed client-side JavaScript

- Never used code directly in the document, always link an external file with the `src` attribute of this element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<script>` supports all global attributes. |
| async | Not required | Specifies that the script is executed asynchronously |
| crossorigin | `"anonymous"`, `"use-credentials"` | Sets the mode of the request to an HTTP CORS Request |
| defer | Not required | Specifies that the script is executed when the page has finished parsing |
| integrity | The file hash often generated with MD5 or SHA256 | Allows a browser to check the fetched script to ensure that the code is never loaded if the source has been manipulated |
| nomodule | `"True"`, `"False"` | Specifies that the script should not be executed in browsers supporting ES2015 modules |
| referrerpolicy | `"no-referrer"`, `"no-referrer-when-downgrade"`, `"origin"`, `"origin-when-cross-origin"`, `"same-origin"`, `"strict-origin"`, `"strict-origin-when-cross-origin"`, `"unsafe-url"` | Specifies which referrer information to send when fetching a script |
| src | Any valid URL | Specifies the URL of an external script file |
| type | Any valid script type as string, the most common are `"application/javascript"` and `"module"` | Specifies the media type of the script |

## Example
```html
<!-- Load a script until the page completes its loading -->
<script src="/assets/js/index.js" async defer></script>

<!-- Load a JavaScript module -->
<script src="/assets/modules/index.mjs" type="module"></script>

<!-- Load a script from another site through CORS -->
<script src="https://www.myapi.com/index.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
```