## Defect Lang

Example:

```
let fib = (x) =>
  if x == 1 then 1 else
  if x == 2 then 1 else
    add(app(fib, add(x, -1)), app(fib, add(x, -2))) in

app(fib, 8)
```

yields `21`.

### Usage

[Main.scala](src/main/scala/Main.scala) has a main function `run` that reads file from file system.

[Lib.scala](src/main/scala/Lib.scala) has a library function `run` that interprets a given string.
