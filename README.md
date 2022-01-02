# JavaScript Cheat Sheet for other languages

## Basic syntax

| JavaScript                         | C#                                 | Python                 |
| ---------------------------------- | ---------------------------------- | ---------------------- |
| `if (#) {} else if (#) {} else {}` | `if (#) {} else if (#) {} else {}` | `if #: elsif #: else:` |
| `console.log(#)`                   | `Console.WriteLine(#)`             | `print(#)`             |
| `let x = 1`                        | `var x = 1`                        | `x = 1`                |
| `'string'`                         | `"string"`                         | `'string'`             |
| `// comment`                       | `// comment`                       | `# comment`            |
| `(a, b) => a + b`                  | `(a, b) => a + b`                  | `lambda a, b: a + b`   |

## Strings

| JavaScript                   | C#                      | Python                  |
| ---------------------------- | ----------------------- | ----------------------- |
| `'a###c'.replace(/#/g, 'b')` | `str.Replace("#", "b")` | `str.replace('#', 'b')` |
| `str.toUpperCase()`          | `str.ToUpper()`         | `str.upper()`           |
| `str.toLowerCase()`          | `str.ToLower()`         | `str.lower()`           |
| `\`Hello ${str}\``           | `$``Hello {str}```      | `f'Hello {str}'`        |

## Lists

| JavaScript        | C#                      | Python                          |
| ----------------- | ----------------------- | ------------------------------- |
| `arr.concat`      | `arr.Concat`            | `arr + arr2`                    |
| `arr.every`       | `arr.All`               | `all`                           |
| `arr.filter`      | `arr.Where`             | `filter`                        |
| `arr.forEach`     | `arr.ForEach`           | `for e in a`                    |
| `arr.indexOf`     | `arr.IndexOf`           | `arr.index`                     |
| `arr.join`        | `String.Join(",", arr)` | `','.join([str(e) for e in a])` |
| `arr.lastIndexOf` | `arr.LastIndexOf`       | N/A                             |
| `arr.map`         | `arr.Select`            | `map`                           |
| `arr.reduce`      | `arr.Aggregate`         | `reduce`                        |
| `arr.reverse`     | `arr.Reverse`           | `arr[::-1]`                     |
| `arr.slice`       | `arr.Skip`              | `arr[#:]`                       |
| `arr.slice`       | `arr.Take`              | `arr[#:#]`                      |
| `arr.some`        | `arr.Any`               | `any`                           |
| `arr.sort`        | `arr.OrderBy`           | `sort`                          |

## Documentation

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- [C#](https://docs.microsoft.com/en-us/dotnet/api/system.linq.enumerable?view=netcore-3.1)
- [Python](https://docs.python.org/3/library/functions.html)
