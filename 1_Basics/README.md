1. Create a new cell, enter: `some_int=10` and execute
2. Crate a new cell, enter: `some_string="10"` and execute
3. Create a new cell, enter `some_float=10.0` and execute
* remember:
    * the name to the left is a 'variable'
    * the `=` sign is an 'assignment operator'
    * the number or text assigned to a variable is the 'value' or 'state' of that variable
4. Create a new cell, execute the following:
```
print(type(some_int))
print(type(some_string))
print(type(some_float))
```
* remember:
    * type() is a built-in python function that returns the type of its argument
    * int stands for integer number
    * str stands for string of characters
    * float stands for floating point number
5. Create a new cell, enter: `type(some_int+1)` and execute
* notice:
    * when you execute a cell, the result of the last instruction is always printed, so you don't have to use print() function
    * when you execute a cell containing variables assingment, those variables are available for all following cells
6. Create a new cell, enter: `type(some_int-1)` and execute
7. Create a new cell, enter: `type(some_int*2)` and execute
8. Create a new cell, enter: `type(some_int*2.0)` and execute
9. Create a new cell, enter: `type(some_int/2)` and execute
* question: why is the type of last 2 cells float?
    * python interprets expressions and assigns them the most suitable type
    * programming languages with this feature are called 'dynamically typed'
10. Create a new cell, enter: `some_int/0` and execute
* remember:
    * if an unexpected or illegal operation is executed, python execution system will throw an `exception`
    * well designed exception should clearly indicate what went wrong
    * you can define and throw your own exceptions, we will explore it in further chapters
11. Create a new cell, enter: `some_string + 1` and execute
* question: can you tell the reason for the exception you see?

    




