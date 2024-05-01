# Part 2
1. At line 12 the code prints 3 because that is the length of the array
2. At line 13 the code prints 150 which is the calculated 
3. At line 14 the code prints 150 which is the calculated finalPrice
4. The function does not return anything because while it returns discounted, nothing is being done to it like console.log which would return the array discounted.
5. At line 12 returns an error because i is not in the same block that line 13 calls it, a reference error. 
6. At line 13 results in an error because discountedPrice is not in the same block that line 13 calls it, a reference error.
7. At line 14 returns 150 because the array discounted is edclared in the same block or scope as line 14.
8. The function returns nothing because while it returns discounted, nothing is being done to it like console.log which would return the array discounted.
9. At line 11 the code will result in an error because i is not declared in the same block as console.log(i) so there is a error in scope.
10. At line 12 it returns the value 3 because that is the lenfrh of the initial array prices which is 3.
11. The function returns nothing to the console as nothing is being done to it, but if console.log was used it would return the array discounted and its length.
12. Notations
    * Accessing the value of the name property in the student object: student.name
    * Accessing the value of the Grad Year property in the student object: student['Grad Year']
    * Calling the function for the greeting property in the student object: student.greeting()
    * Accessing the name property of the object in the Favorite Teacher property in student: student['Favorite teacher'].name
    * Access index zero in the array of the courseLoad property of the student object: student.courseLoad[0]

13. Arithmetic
    * '3' + 2 = 32 since using + operator with string '3' and integers map to their exact string representation it concatenates 2 at the end instead of numerical addition.
    * '3' - 2 = 1 when useing - the string '3' is concerted to a number than performs substraction so 3 - 2 = 1
    * 3 + null = 3 because wehn null is used in numerica operators it is treated as a 0
    * '3' + null = 3null using the + sign will concatenate the string '3' with string null
    * true + 3 = 4 since true has binary value 1 so 1 + 3 = 4
    * false + null = 0 since false has binary value 0 and null is 0, 0 + 0 = 0
    * '3' + undefined = 3undefined using the + sign will concatenate the string '3' with string undefined
    * '3' - undefined = nan which stands for not a number because you can not perform subtraction between a string an undefined, so it is not a valid arithmetic operation.

14. Comparison
    * '2' > 1 = true because comparing string with number using > converts the string to a number before comparison so 2 > 1 is true
    * '2' < '12' = false because when comparing two strings
    * 2 == '2' = true because the == operator will perform a type conversion before comparing 
    * 2 === '2' = false because the === operator does not perform type converion and vecks both the value and type so since they are two different types it evaluates to false.
    * true == 2 = false because the == converts the true to its binary value 1 so 1 == 2 is false
    * true === Boolean(2) = true because the === operator checks the value without converting so true is a boolean and Boolean(2) is a true because any non-zero number is considered true.
   
15. The difference between == and === operators are that == does type conversion of operands before comparison and === compares values and data types of operands. In short == performs conversion before comparing values and === comapres vales and types stricly and helps avoid unexpected behavior caused by converion.

16. []() \ the output should is 21 45 5 2

17. 
    
