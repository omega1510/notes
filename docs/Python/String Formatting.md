# String Formatting
---

| Format String  | Sample Output    | Comments                                                                                |
| -------------- | ---------------- | --------------------------------------------------------------------------------------- |
| `%d`           | `24`             | Use `d` with [[Literals#Integer Literals]].                                                                |
| `%5d`          | `___24 `         | Spaces are added so that the field width is 5.                                          |
| `$05d`         | `00024`          | If you add `0` before the field width, zeroes are added instead of spaces.              |
| `Quantity:%5d` | `Quantity:___24` | Characters inside a format string but outside a format specifier appear int he output. |
| `%f`           | `1.21997`        | Use `f` with [[Literals#Float Literals]].                                                   |
| `%.2f`         | `1.22 `          | Prints two digits after the decimal point.                                              |
| `%7.2f`        | `___1.22`        | Spaces are added so that the field width is 7.                                          |
| `%s`           | ` Hello `        | use `s` with [[Literals#String Literals]].                                                                  |
| `%d %.2f`      | `24_1.22 `       | You can format multiple values at once.                                                 |
| `%9s`          | `____Hello`      | Strings are right-justified by default.                                                 |
| `%-9s`         | `Hello____`      | Use a negative field width to left-justify.                                             |
| `%d%%`         | `24%`            | To add a percent sign to the output, use `%%`.                                          |

Related: [[Literals]], [[f-strings]]