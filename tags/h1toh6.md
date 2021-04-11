# The heading elements
The `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` and `<h6>` are headings for our content.

- The `<h1>` element is the biggest one, and can only be one per document
- The rest of the heading elements are for subtitles for each section
- Every heading element can only be dependant of the heading element with an immediate lower number, thus, the `<h1>` element is the mpst important and `<h6>` element the least important
- A good organization of the heading elements means a better SEO

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` and `<h6>` support all global attributes. |

## Example
```html
<h1>Kingdom: Animalia</h1>
<h2>Phylium: Chrodata</h2>
<h3>Class: Mammalia</h3>
<h4>Order: Primates</h4>
<h5>Genus: Homo</h5>
<h6>Species: H. Sapiens</h6>
```