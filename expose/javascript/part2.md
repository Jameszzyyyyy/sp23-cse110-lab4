# Part 2 solution

1. It is going to print "3", because variable `i` is a `var` variable, it can be referenced outside the block it is in. And since there are three element in the `prices`, `i` will be 3 after the loop.

2. It is going to print `150`, similar as the first question, after the loop, the `discountedPrice` will be 150.

3. It is also going to print `150`, the only difference between `discountedPrice` and `finalPrice` is that `finalPrice` is rounded to integer. Since `discountedPrice` is a integer, it wound change the value.
