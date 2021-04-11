# The `<main>` element
Defines the main content in the document

- There must only be one `<main>` element
- Must not contain repetitive content, such as sidebars, navigation links, copyright information, site logos, and search forms
- The `<main>` element must **NOT** be a descendant of an `<article>`, `<aside>`, `<footer>`, [`<header>`](header.md), or [`<nav>`](nav.md) element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<main>` supports all global attributes. |

## Example
```html
<!-- The doctype tag -->
<!-- The opening html tag -->
    <!-- The opening body tag -->
        <main>
            This is my main content, the reason why you clicked in the link to this document. May be my article or my tutorial content, as an example.
        </main>
    <!-- The closing body tag -->
<!-- The closing html tag -->
```