# The `<picture>` element
Defines a container for image resources

- This element is useful to define a different image source in different viewport widths
- This element can only have one or more [`<source>`](source.md) elements and only one [`<img>`](img.md) element as children
- The image [`<source>`](source.md) to be displayed will be selected by the viewport width, and the [`<img>`](img.md) element serves as fallback to all of them
- The first image that matches the viewport width will be used

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<picture>` supports all global attributes. |

## Example
```html
<picture>
  <!-- Any number of <source> elements with media (example: min-width:650px) and srcset (example: img_pink_flowers.jpg) attributes set -->
  <!-- An <img> element as fallback -->
</picture>
```