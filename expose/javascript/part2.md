# Part 2

1. At line 12, 3 will be printed. This is because `var` isn't contained within the code blocks, so it can be called and referenced outside the for loop.
2. At line 13, 150 will be printed. The `var` variable isn't contained within the code blocks, so it can be called and referenced outside the for loop.
3. At line 14, 150 will be printed. The variable was able to be called by the statement since it was defined at the top of the function. 
4. This function will return an array of discounted prices. First the empty array gets initialized via the `var` keyword. Then, the prices get evaluated in the for loop before being pushed to the array. 
5. Line 12 will cause an error. This is because `let` is contained within code blocks, and since the console statement is outside the for loop, there is no `i` variable that is defined.
6. Line 13 will cause an error. The `let` variable is contained within the code blocks, so it can't be called or referenced outside the for loop.
7. At line 14, 150 will be printed. The `let` variable is declared and contained in the same code block as the console statement, so the value will be updated in the for loop before being called in the console statement.  
8. This function will return an array of discounted prices. The empty array gets initialized with the `let` keyword and the return statement is in the same code block, so the array will be returned. The values get updated with the push inside the for loop.
9.  Line 11 will cause an error. This is because `let` is contained within code blocks, and since the console statement is outside the for loop, there is no `i` variable that is defined.
10. At line 12, 3 will be printed. There is a constant value of length, which is the length of the prices array. Since that value of 3 never gets changed, no error appears there. The console statement is also in the same code block as the `const` variable, so that's why we can reference that in the console statement.
11. The function will return an array of discounted prices. The initial reference to the array gets initialized with the `const` keyword and the return statement is in the same code block, so the array will be returned. We can still update the values inside the array however, which is why they get updated with the push inside the for loop without causing an error.
12. Objects
    1. `student.name;`
    2. `student['Grad Year'];`
    3. `student.greeting();`
    4. `student['Favorite Teacher'].name;`
    5. `student.courseLoad[0];`
13. Arithmetic
    1.  '32', the `+` sign was used for concatenating two strings since a string was used ('3'). 
    2.  1, the `-` sign is a mathematical operator and converted the string to a number (3 - 2 = 1).
    3.  3, the `null` has a numerical value of 0 so it converted `null` to 0 and did addition (3 + 0 = 3).
    4.  '3null', the `+` sign was used for concatenating two strings since a string was used.
    5.  4, `true` has a numerical value of 1 so it converted `true` to 1 and did addition.
    6.  0, `false` and `null` both have numerical values of 0 so it converted both to 0 and did addition.
    7.  '3undefined', the `+` sign was used for concatenating two strings since a string was used.
    8.  'NaN', the `-` sign is a mathematical operator so it tried to convert a string to a number, but it failed since `"undefined"` is not a number.
14. Comparison
    1.  True, the string gets converted to a number and 2 is greater than 1.
    2.  False, the char '2' is greater than the char '1' which made the statement false.
    3.  True, the string gets converted to a number and 2 is equal to 2.
    4.  False, the number 2 is not equal to the string '2'.
    5.  False, `true` gets changed into the number 1 and 1 is not equal to 2.
    6.  True, `Boolean(2)` evaluates to true and the boolean true is equal to the boolean true.
15. The == operator allows for type conversion, while the === does not allow for type conversion.
16. Go to [part2-question16.js](part2-question16.js)
17. The result is that `newArr` will return as an array with the values 2, 4, and 6. At the start of the function call, the array `[1, 2, 3]` and the callback function `doSomething` are passed into the `modifyArray` function. Then `newArr` is made and pushes the value returned by the callback function, which was the number in that element times 2. After that, `newArr` is returned with the new values.
18. Go to [part2-question18.js](part2-question18.js)
19. The output of the code is `1, 4, 3, 2` respectively.