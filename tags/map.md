# The `<map>` element
Defines a client-server image map

- This element can be linked to an `<img>` element through  the `usemap` attributes
- Enables certain areas of an image to be clicked and reference another document
- This element can only have `<area>` children

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<map>` supports all global attributes. |
| name | Any string | **Required**. Specifies the name of the image map |

## Example
```html
<!-- An im element that has the attribute usemap with the value #myphoto -->
<map name="myphoto">
    <!-- Any number of <area> elements -->
</map>
```