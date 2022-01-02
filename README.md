# JavaScript Cheat Sheet for other languages

| JavaScript    | C#                      |
| ------------- | ----------------------- |
| `concat`      | `Concat`                |
| `every`       | `All`                   |
| `filter`      | `Where`                 |
| `forEach`     | `ForEach`               |
| `indexOf`     | `IndexOf`               |
| `join`        | `String.Join(str, arr)` |
| `lastIndexOf` | `LastIndexOf`           |
| `map`         | `Select`                |
| `reduce`      | `Aggregate`             |
| `reverse`     | `Reverse`               |
| `slice`       | `Skip`                  |
| `slice`       | `Take`                  |
| `some`        | `Any`                   |
| `sort`        | `OrderBy`               |

The table bellow shows how some methods can be replicated using one line codes.

| JavaScript                                 | C#               |
| ------------------------------------------ | ---------------- |
| `arr.reduce((a, b) => a + b) / arr.length` | `Average`        |
| `arr.length`                               | `Count`          |
| `arr.length ? [def] : arr`                 | `DefaultIfEmpty` |
| `arr[index]`                               | `ElementAt`      |
| `arr.length ? arr[0] : def`                | `FirstOrDefault` |
| `arr.length ? arr[arr.length - 1] : def`   | `LastOrDefault`  |
| `Math.max.apply(this, arr)`                | `Max`            |
| `Math.min.apply(this, arr)`                | `Min`            |
| `arr.reduce((a, b) => a + b)`              | `Sum`            |
