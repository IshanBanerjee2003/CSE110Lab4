    Question 1:

1. This line will print 3. The reason behinf that is because the loop runs thrice, that it specifically 0, 1, 2 and updates one last time to become 3. 
2. This will print 150 simply because Discounted Price is of var type and its scope exists in the whole file. 
3. This shall also print 150 because it has also been declared as a var type and its scope is outside the whole file.
4. This function returns an array : [50,100,150]. This is simply the return value of the function.
5. 'i' is not defined because it is defined with let and is out of scope now. 
6. 'Discounted Price' is not defined because it is defined with let and is out of scope now.
7. Line 14 prints 150, since it is in scope of the function, and is defined with let.
8. This function will also return an : [50,100,150]. Despite being declared with let, the computation in the function happens correctly and the return value is accurate. 
9. This will not print anything, since const values are being reassigned in the code and that throws an error.
10. This prints 3, which is basically the length of the array.
11. It prints the following array :  [50,100,150]. This is because the const value has not been reassigned. 
    
    Question 2:
A. student.name
B. student["Grad Year"]
C. student.greeting()
D. student["Favorite Teacher"].name
E. student.courseLoad[0]

    Question 3:
A. '32' is the output as this part just appends '2' to the string '3', and doesnt add them arithmatically. 
B.  1 is the output for the following part, as it is treating both 3 and 2 as numbers and by arithmatic subtraction 1 is returned.
C.  3 is returned as 3 is treated numerically and null is read as 0, hence returning 3.
D.  '3null' is returned as both these are treated as strings and hence they are appended.
E.  4 is returned simply because true has been treated as 1 and then arithmatically added to 3.
F.  0 is returned by this part, because the term false has been arithmatically treated as 0 and the fact that it has been added to a null.
G.  '3undefined' is returned as it treates both as a concatenation of two strings.
H. Nan is returned as we simply cannot subtract undefined, which is not a number.

    Question 4:
A. This returns true because it converts '2' to a number and compares it with 1, leading to the comparison aspect.
B. This returns false because '2' has a higher unicode value than '12'.
C. This returns true because the == operator will always be using type coercion and treats both the operands as numbers.
D. This returns false as the === operator will not be using type coercion and just checks the equality thus returning false.
E.  This returns false because the == operator uses type coercion and shall be treating true as 1.
F.  This returns true as Boolean(non zero number) is always true, which is being satisfied in this case.

    Question 5:
This returns false as the == operator will be using type coercion and the === operator will not be using type coercion, hence will immediately return false, if they are of different types.

    Question 17:
modifyArray([1,2,3]) changes the passed array and returns [2,4,6]. WHat this basically does is modifyArray will edit every element in the array depending on the function passef through it, and this particular function is called callback.

    Question 19:
1
4
3
2




