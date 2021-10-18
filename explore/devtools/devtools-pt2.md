# Devtools Part 2

1. The bug is that both values `num1` and `num2` are characterized as strings, so the sum function sets `result` to be a string and concatenates the two values. 
2. I would fix it by calling `Number(num1)` and `Number(num2)` when the `result` variable is being initialized, so that it treats the `+` sign as a mathematical operator and not a string operator where it concatenates. (See [fix.png](fix.png))