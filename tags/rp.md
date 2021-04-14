# The `<rp>` element
Defines text to be displayed in browsers that do not support ruby annotations

- Useful to show parentheses in browsers that do not support ruby annotations

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<rp>` supports all global attributes. |

## Example
```html
<!-- A ruby annotation element opening tag -->
    漢
    <!-- A ruby explanation element opening tag -->
        <rp>(</rp>
        ㄏㄢˋ
        <rp>)</rp>
    <!-- A ruby explanation element cloing tag -->
<!-- A ruby annotation element closing tag -->
```