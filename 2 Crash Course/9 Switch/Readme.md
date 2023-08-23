## 9. Switch

If you have many conditions you want to compare, you can use `switch` statements.

```c++
int day = 4;
switch (day) {
  case 1:
    cout << "Monday";
    break;
  case 2:
    cout << "Tuesday";
    break;
  case 3:
    cout << "Wednesday";
    break;
  case 4:
    cout << "Thursday";
    break;
  case 5:
    cout << "Friday";
    break;
  case 6:
    cout << "Saturday";
    break;
  case 7:
    cout << "Sunday";
    break;
  default:
    cout << "Looking forward to the Weekend";
}
// Outputs "Thursday" (day 4)
```

- If the value of `day` matches a case value, then only that code block will execute. 
- Once a matching `case` has been found then none of the other cases will be checked.
- If there was no matching case then the `default` code block will execute. 
  - Including a `default` case is optional.

### Difference between `switch` and `if-else` statements

| `if-else` | `switch` |
| - | - |
| Only a single statement is executed | All statements are executed until `break;` is encountered |
| Statement tests for any kind of comparison (>, <, >=, etc.) | Statement only tests for equality |
| Each comparison may contain different variables | Only a single variable is evaluated |

## References
- [Difference between if-else and switch](https://www.tutorialspoint.com/difference-between-if-else-and-switch)
