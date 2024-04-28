1. What was the bug?
The bug was that the input was saved as a string within num1 and num2, so when the + operator was used on them, it just resulted in string concatenation rather than number addition. 
2. How would you fix it?
I would fix it by converting the input to a number and saving this value in new variables. I would also check if these new variables have a type "number", or return false if the conversion was not successful.  