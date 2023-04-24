# Part 2 solution

1. It is going to print "3", because variable `i` is a `var` variable, it can be referenced outside the block it is in. And since there are three element in the `prices`, `i` will be 3 after the for loop.

2. It is going to print `150`, similar as the first question, after the for loop, the `discountedPrice` will be 150.

3. It is also going to print `150`, the only difference between `discountedPrice` and `finalPrice` is that `finalPrice` is rounded to integer. Since `discountedPrice` is a integer, it wound change the value.

4. It is going to print `[50,100,150]`, because `discounted` contains prices after the discount, so we apply the `discount` to each of value inside `price`.

5. It is going to cause an error, because `i` is a `let` variable, it can only be referenced inside its for loop block.

6. It is going to cause an error, because `discountPrice` is a `let` variable, which can only be referenced within the same block it is declared, so calling it at line 13 will cause an error.

7. It is going to print `150`, `finalPrice` is a `let` variable declared in the same block where line 13 at, so it will print the value of it after the for loop, which is `150`.

8. It is going to print `[50,100,150]`, `discounted` is declared in the same block where line return is, because `discounted` contains prices after the discount, so we apply the `discount` to each of value inside `price`.

9. It is going to cause an error, because `i` is a `let` variable, we have no access to it outside its block.

10. It is going to print `3`, `length` is a `const` variable within the same block where line 12 at, and we've never reassigned its value.

11. It is going to print `[50,100,150]`, which is same as in question 4 and question 8. Although `discounted` is a `const` variable, we never reassigned its value, instead we only altered its constant array, so it won't cause any issue.

12. [A] student.name

    [B] student["Grad Year"]
    
    [C] student.greating()
    
    [D] student["Favorite Teacher"].name
    
    [E] student.courseLoad[0]

13. [A] Answer: '32'. Explanation: since we have a string, we concentrated the string version of the integer `2` with the string `'3'`.

    [B] Answer: 1. Explanation: since there is no string operation using `-` operator, we conver `'3'` to its integer version.
    
    [C] Answer: 3. Explanation: `null` maps to 0 in integer, so 3+0=3.
    
    [D] Answer: '3null'. Explanation: since we have a string `'3'` we concentrate it with `null`.
    
    [E] Answer: 4. Explanation: `true` maps to 1 in integer, so 1+3=4.
    
    [F] Answer: 0. Explanation: both `false` and `null` map to 0, 0+0=0.
    
    [G] Answer: '3undefined'. Explanation: since we have a string `'3'`, we concentrate it with `'undefined'`
    
    [H] Answer: NaN. Explanation: since there is no string operation using `-` operator, we have to convert both into integer, but `undefined` cannot map to any integer, so the result is 'Not a Number'.

14. [A] Answer: true. Explanation: '2' converts to 2, 2 > 1.
  
    [B] Answer: false. Explanation: dictionary comparison, first char "2" is not smaller than the first char "1"
    
    [C] Answer: true. Explanation: '2' converts to 2, 2 == 2.
    
    [D] Answer: false. Explanation: strict equality check `===`, they are not same.
    
    [E] Answer: false. Explanation: true converts to 1, 1 != 2
    
    [F] Answer: true. Explanation: `Boolean(2)` is same as the boolean value `true`.
    
15. `==` is a non-strict check, it will perform type conversions to make the two arguments the same type; `===` is a strict equality check, where it compare values directly without conversion.

16. See [part2-question16.js]().

17. 










