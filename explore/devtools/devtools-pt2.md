1. The bug is that whenever the user input the `num1` and `num2`, these two variables are both `string`, so that when we do `+` operation, it will concentrate them.

2. It is kinda simple to fix it, I used `parseInt()` to convert both `num1` and `num2` to `Integer`, so that now `+` operation will perform as what we want.
