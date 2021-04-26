## Part 1a
1) 20
2) 20
3) 20
4) error: result is not defined/doesn't exist outside of the if statement since 'let' is only valid within that scope
5) error: can't reassign const variable
6) error: result is not defined outside of the if statement since const is only valid within that scope
## Part 1b
1) It will print 3. since that is the last value that i is incremented to in the loop and var has a universal scope within all of the function
2) After the last iteration of the for loop 150 will be printed. This is because even though discountedPrice is initialized within the for loop scope, it is a var variable which will have scope throughout the function.
3) After the last iteration of the for loop 150 will be printed. This is because even though finalPrice is updated within the for loop scope, it is a var variable which will have scope throughout the function.
4) It returns the discounted array which includes [50, 100, 150]. discounted scope is the whole function since it is a var variable but this also doesnt matter because it is initialized before the forloop and then updated within it by getting the final price for 3 iterations.
5) error: i is defined within the scope of the forloop and the let variable is only able to be used within the scope it was defined in.
6) error: discountedPrice is defined within the scope of the forloop and the let variable is only able to be used within the scope it was defined in and the variable does not exist outside fo that scope. Additionally you can't redeclare a let variable as it tries with each new iteration.
7) 150 will be printed. The finalPrice let variable was defined and intialized before the for loop so its scope is the rest of the function and therefore can be updated in the loop and printed out after.  
8) The function will return the discounted array which includes [50, 100, 150]. Even though discounted and finalPrice are let variables, they are declared at the begining of the function so they can be used throughout the rest of th efunction and updated within the scope to then return discounted in the end and the let discountedPrice is only used within the for loop.
9) error: i is defined within the scope of the forloop and the let variable is only able to be used within the scope it was defined in. i does not exist outside of the loop.
10) It will print 3 since const length is set at the beginning of the function and not updated as it shouldn't be.
11) The function will return the discounted array which includes [50, 100, 150]. You can modify const arrays.
12) 
    ```
    a)  student.name
    b)  student['Grad Year']
    c)  student.greeting()
    d)  student['Favorite Teacher'].name
    e)  student.courseLoad[0]
    ```
13) <br>
    a) '32' - since integers map to their exact string representation<br>
    b) 1 - '3' take sthe int form to do 3-2 = 1<br>
    c) 3 - since null becomes 0 with numeric conversion<br>
    d) '3null' - null just becomes a string with the name null<br>
    e) 4 - true becomes 1 with numeric conversion<br>
    f) 0 - false becomes 0 and null becomes 0 with numeric conversions<br>
    g) '3undefined' - undefined becomes the string form and is concatenated to 3<br>
    h) NaN - subtraction with non-numbers is NaN<br>
14) <br>
    a)  true - string '2' becomes number 2<br>
    b)  false - compares the string values in lexicographical order<br>
    c)  true - string '2' becomes number 2<br>
    d)  false - string '2' becomes number 2, === says false because string and integer are different <br>
    e)  false - true becomes 1<br>
    f)  true - Boolean(2) is false, and === is to check if true and false are not equal so thats true<br>
15) === (Triple equals) is a strict equality comparison operator in JavaScript, which returns false for the values which are not of a similar type. While == is just a regular equality checker that doesn't pay attention to variable type.
16) The result will be [2,4,6] because you are using the function that is passed into modifyArray which doubles a number and this callback function is doubling the value at that array index and pushing it onto the new array you are making for each iteration of the forloop.
17) ans:
    ```
    1
    4
    3
    2
    ```
