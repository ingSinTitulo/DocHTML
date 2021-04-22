# The `<meter>` element
Defines a scalar measurement within a known range

- Also can represent a fractional value
- It is also known as a gauge
- Useful to represent the completeness of a profile, for example

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<meter>` supports all global attributes. |
| `form` | Any existing form id | Specifies which form the `<meter>` element belongs to |
| `high` | Any number | Specifies the range that is considered to be a high value |
| `low` | Any number | Specifies the range that is considered to be a low value |
| `max` | Any number | Specifies the maximum value of the range |
| `min` | Any number | Specifies the minimum value of the range. Default value is 0 |
| `optimum` | Any number | Specifies what value is the optimal value for the gauge |
| `value` | Any number | Required. Specifies the current value of the gauge |

## Example
```html
<meter id="profile_completeness" value="2" min="0" max="10">You have completed 2 steps out of 10 to complete your profile</meter>
```