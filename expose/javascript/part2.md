1. The code will print 3. This happens because i is declared as a var, which can be accessed function-wide.
2. The code will print 150. This happens because discountedPrice is desclared as a var, which can be accessed function-wide.
3. The code will print 150. This happens because finalPrice is declared as a var, which can be accessed function-wide.
4. The function will return an array \[50, 100, 150\]. This happens because discounted is a var and can be accessed function-wide. The for loop pushes the finalPrice values to the discounted array.
5. The code causes an error because it tries to access a variable declared out of scope. The variable i is declared as a let in a for loop.
6. The code causes an error because it tries to access a variable declared out of scope. The variable discountedPrice is declared as a let in the for loop.
7. The code will print 150. This happens because even though finalPrice is declared as a let, it still is in the same scope as this line of code.
8. This function will return an array \[50, 100, 150\]. This happens because discounted can still be reassigned and accessed from line 16.
9. The code causes an error because it tries to access a variable declared out of scope. The variable i is declared as a let in the for loop.
10. The code will print 3. This happens because length is declared as a const in the same scope as line 12 and it is not being reassigned.
11. The code will return an array \[50,100,150\]. This happens because none of the const variables are being reassigned to another value. The discounted variable is only being modified by being pushed values, but not being reassigned a new array. Each variable is also only used in their scope.
12. Question 12
    1.  student.name
    2.  student\["Grad Year"\]
    3.  student.greeting()
    4.  student\["Favorite Teacher"\].name
    5.  student.courseLoad[0]
13. Question 13
    1.  32
    2.  1
    3.  3
    4.  3null
    5.  4
    6.  0
    7.  3undefined
    8.  NaN
14. Question 14
    1.  true
    2.  false
    3.  true
    4.  false
    5.  false
    6.  true
15. The == operator checks equality with type conversion while the === operator checks equality without type conversion.
17. The result would be an array \[2,4,6\]. The function modifyArray accepts the array \[1,2,3\] and the function doSomething. Then, it creates a const newArray array variable. Then, it iterates through the input array and pushes values that have been outputted from the callback function, which is doSomething, into newArr. Finally, it returns newArr, being \[2,4,6\].
19. 1
    4
    3
    2