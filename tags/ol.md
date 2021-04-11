# The `<ol>` element
Defines an ordered list

- The immediate children of this element can only be [`<li>`](li.md) elements, that will be the ordered list items or other lists ([`<ul>`](ul.md) or `<ol>`)
- By default, the list items in an ordered list appear as incremental numbered items, but if it is a nested list or by configuration, it can change to letters and be reversed

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<ol>` supports all global attributes. |
| reversed | Not required | Specifies that the list order should be reversed (9,8,7...) |
| start | Any valid unsigned integer number | Specifies the start value of an ordered list |
| type | `"1"`, `"A"`, `"a"`, `"I"`, `"i"` | Specifies the kind of marker to use in the list |

## Example
```html
<ol>
    <!-- here is where you must put your ordered list items -->
</ol>
```