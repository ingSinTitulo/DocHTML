# The `<head>` element
Is a container for metadata about the document.

- `<head>` and its child elements are not displayed in the page.
- Is child of the [`<html>`](html.md) element
- The document can have just one `<head>` element
- It is parent for the next elements
    - `<title>` mandatory for SEO
    - `<style>` not recomended as all styles should be in a separated file
    - `<base>` optional
    - `<link>` optional
    - `<meta>` mandatory for defining the charset of the document, but all other `<meta>` possible elements are optional
    - `<script>` optional
    - `<noscript>` optional

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