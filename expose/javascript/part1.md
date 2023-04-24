#Part1 Solution#

1. line 9 will print "values added: 20"
2. line 13 will print "final result: 20"
3. line 9 will print "values added: 20"
4. line 13 will cause an error because `result` is a `let` variable declared in the conditional block, referencing it outside the block causes error
5. line 9 will cause an error because `result` is a `const` variable so that it cannot be changed (in line 7) after declaring
6. line 13 will cause an error because same as `let` variable, `const` variable can only be referenced within the same block it is declared.

