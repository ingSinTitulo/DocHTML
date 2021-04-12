# The `<head>` element
Is a container for metadata about the document.

- `<head>` and its child elements are not displayed in the page.
- Is child of the [`<html>`](html.md) element
- The document can have just one `<head>` element
- It is parent for the next elements
    - [`<title>`](title.md) mandatory for SEO
    - [`<style>`](style.md) not recomended as all styles should be in a separated file
    - [`<base>`](base.md) optional
    - [`<link>`](link.md) optional
    - [`<meta>`](meta.md) mandatory for defining the charset of the document, but all other [`<meta>`](meta.md) possible elements are optional
    - [`<script>`](script.md) optional
    - [`<noscript>`](noscript.md) optional

## Atributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<head>` supports all global attributes. |

## Example
```html
<!-- This head element must be always inside an html element, and must be always just one -->
<head>
    <!-- Here goes the title -->
    <!-- Here goes the charset of the document, usually UTF-8 -->
</head>
```