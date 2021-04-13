# The `<time>` element
Defines a time or a datetime

- Used to translate the time into a machine-readable format
- This time can be used by browsers to add date reminders through the user's calendar
- Search engines use this data to show only the most recent results
- Useful in blogs and news sites to add a time when the article was written

## Attributes
| Name | Posible values | Notes |
|-|-|-|
| [Global attributes](../first-steps/global-attributes.md) | N/A | `<time>` supports all global attributes. |
| `datetime` | Any valid datetime string | Represent a machine-readable format of the `<time>` element |

## Example
```html
Earn money selling feet photos
By Alan Ztarain - <time datetime="2021-04-12 20:00">12 Apr '21</time>
```