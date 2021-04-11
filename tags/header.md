# The `<header>` element
Defines the header for the document or for a section within the document

- This element should contain the presentation information (Logo, a [heading element](h1toh6.md) and an introduction)
- Optionally, if the presentation is not needed and this element is the header of the document, you can use this element as the parent for the [`<nav>`](nav.md) element of our document
- Each section of the document can contain a `<header>` element
- The `<header>` cannot be placed within a `<footer>`, `<address>` or another `<header>` element

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<header>` supports all global attributes. |

## Example
```html
<!-- This is the main header of our document -->
<header>
    <!-- Logo -->
    <!-- Web site name -->
    <!-- Web page title -->
</header>

<!-- This is the main header of our document -->
<header>
    <!-- The opening tag of a <nav> element -->
        <!-- Our navigation links -->
    <!-- The closing tag of a <nav> element -->
</header>
```