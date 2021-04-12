# The `<noscript>` element
Defines alternative text to be shown if the client does not have JavaScript enabled.

- Can be both inside [`<head>`](head.md) and [`<body>`](body.md) elements
- If it is inside [`<head>`](head.md), it can only contain [`<link>`](link.md), [`<style>`](style.md) and [`<meta>`](meta.md) elements

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<noscript>` supports all global attributes. |

## Example
```html
<noscript>Your browser does not support JavaScript. Enable JavaScript or use another browser to use this application</noscript>
```