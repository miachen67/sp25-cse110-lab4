1. The program will print 3 to the console because we used `var` to declare `i`, which means that it has function scope so it is still valid outside of the for loop. Since the length of prices is 3, i = 3 at the end of the loop.
2. The program will print 150 to the console because we used `var` to declare `discountedPrice`, which means that it has function scope so it is still valid outside of the for loop. Since the last item had a discounted price of 150, the value of `discountedPrice` is still 150 outside of the loop. 
3. The program will again print 150 because we used `var` to declare finalPrice as well. So the last item had a finalPrice of 150 and since the scope of the variable is function scope, the finalPrice will be 150 when printed. 
4. The function will return [50, 100, 150] because we are pushing the final price of each item to an array `discounted` and returning that array. 
5. There is an error at line 12 because `i` follow block scope due to declaring it with the keyword `let` meaning it was only valid inside the for loop. Now that we have exited the loop, `i` is no longer in scope.
6. Similarly, at line 13, `discountedPrice` is also no longer in scope. It was declared with a `let` keyword in the for loop so it is only valid in the for loop.  
7. There is no error and the program prints 150 to the console. This is because finalPrice was declared with the `let` keyword inside the function and it is still accessible in line 14. 
8. This function will return [ 50, 100, 150 ] because we are pushing the final price of each item to an array `discounted` and returning that array.
9. There will be an error because `i` follows block scope due to declaring it with the keyword `let` meaning it was only valid inside the for loop. Now that we have exited the loop, `i` is no longer in scope.
10. The program will print 3 since the length of prices is 3. 
11. This function will return [50, 100, 150] since we are pushing the discounted price into an array and returning that array.
12. Object
    A.  `student.name`
    B.  `student['Grad Year']`
    C.  `student.greeeting`
    D.  `student['Favorite Teacher'].name`
    E.  `student.courseLoad[0]`
13. Arithmetic
    A. '32' because the 2 is converted to its exact string representation
    B. 1 since the 3 is now converted to its integer representation
    C. 3 since null becomes 0
    D. '3null' since null is converted to its exact string representation
    E. 4 since true = 1
    F. 0 since false is 0 and null is also 0
    G. '3undefined' because undefined's string representation is 'undefined'
    H. NaN because undefined's numberic conversion is NaN
14. Comparison
    A. true because '2' gets converted to 2
    B. false because lexographically, '2' is greater than '12'
    C. true because '2' is converted to 2
    D. false because they are of different types
    E. false because true = 1
    F. true because Boolean(2) = true
15. == compares two values after doing type conversions but === checks for strict equality without doing any conversions. 
    
17. `modifyArray([1, 2, 3], doSomething)` would return an array `[2, 4, 6]`. We passed the array `[1, 2, 3]` and function `doSomething` as arguments to `modifyArray`. In `modifyArray` a new array is initalized and a for loop, which iterates over the array passed into `modifyArray`. In each iteration of the for loop, an element of `array` is passed into the function passed into `modifyArray`. In this case `doSomething` doubles each element, giving us the output `[2, 4, 6]`. 
18. `printNums()` will print 1 to the console, and while waiting one second to print 2, it will print 4 (first since there is no setTimeout here) and then 3. Finally, after 1 second, it will print 2. 

