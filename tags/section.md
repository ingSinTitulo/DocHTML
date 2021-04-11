# The `<section>` element
Defines a section in the document

- Works pretty much exactly as de [`<div>`](div.md) element. But its main difference is semantic. Search engines (SEO) list the sections as part of the result, with its [heading element](h1toh6.md) as title.
- Use this to list each section that could be accessed by an anchor link

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<section>` supports all global attributes. |

## Example
```html
<!-- The doctype tag -->
<!-- The opening html tag -->
    <!-- The opening body tag -->
        <!-- A main heading element -->

        <section>
            <!-- A second level heading element, that will serve as the section title -->
            <!-- Section content -->
            
            <section>
                <!-- A third level heading element (and so on...), that will serve as the section title -->
                <!-- Section content -->
            </section>
        </section>

        <section>
            <!-- A second level heading element, that will serve as the section title -->
            <!-- Section content -->
        </section>
    <!-- The closing body tag -->
<!-- The closing html tag -->
```