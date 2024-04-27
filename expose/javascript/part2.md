1. It would print 3. This is because variables declared as var are able to be accessed from outside of a for block. Since prices.length is 3 and the for loop stops at that value of i, i=3 at that point in the code. 
2. It would print 150. This is because variables declared as var are able to be accessed from outside of a for block. The latest value of discountedPrice would occur in the final iteration of the for loop, which is prices[2] * (1 - discount) = 300 * (0.5) = 150
3. It would print 150. This is because finalPrice is updated within the for loop. At the final iteration, finalPrice = Math.round(discountedPrice * 100) / 100, and since we know discountPrice is 150, finalPrice would also be 150. 
4. [50, 100, 150]. Since the discount is 0.5, each price is halved, resulting in this array,
5. This would throw an error, since i is not defined. This is due to i only declared in the for block using the let keyword, which means it would be out of scope at line 12.
6. This would throw an error, since discountedPrice not defined. This is due to discountedPrice only declared in the for block using the let keyword, which means it would be out of scope at line 12.
7. This would print 150. finalPrice is declared with the let keyword, but it does so within the same code block that the line 14 is in, so it is able to access the variable without issue. It is also updated within the for loop, so its value would reflect the rounded discountedPrice, which is 150.
8. This would return [50, 100, 300]. It would operate pretty much the same as when the variables were declared with var, except i and discountedPrice would not be accessible outside of the for loop. Since the console.log() statements are commented out, no errors would be thrown. 
9. The code would thrown an error, since i is declared using the let keyword and it would be local to the for block. Thus, at line 11, it would claim that i is not defined. 
10. It would print 3. length is equivalent to prices.length. Since the array passed has a length of 3, the print statement would also show 3. 
11. It would return [50, 100, 150] as expected. While discountedPrice was declared with const, it is not reassigned anywhere in the code, so the function would apply the 0.5 discount to the array as desired.
12. A. student.name;
B. student['Grad Year'];
C. student.greeting();
D. student['Favorite Teacher'].name;
E. student.courseLoad[0];
13. A. '32' since 2 maps to '2'. 
B. 1 since '3' maps to 3.
C. 3 since null converts to 0.
D. '3null' since null converts to 'null'
E. 4 since true maps to 1.
F.  0 since false maps to 0 and null maps to 0
G. '3undefined' since undefined maps to 'undefined'
H. NaN since a numerical value should be returned but undefined does not map to a numerical value. 
14. A. True because '2' maps to 2.
B. False because '2' maps to 2 and '12' maps to 12.
C. True because '2' maps to 2.
D. False because === type checks and 2 and '2' are different types.
E. False because true maps to 1.
F. True because Boolean(2) returns true. 
15. == checks if the operands can be mapped to value that is equivalent, === checks if the operands are the same type and value.
17. The output would be [2, 4, 6]. Within modifyArray(), array is iterated through. At each iteration, newArr is pushed a new value equivalent to the result of the callback function at array[i]. Since the callback is a function that doubles the number, the result is [1*2, 2*2, 3*2] = [2, 4, 6].
19. The output is:
1 
4
3
2