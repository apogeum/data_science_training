  remember:  
  to create a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>C</kbd>  
  to run a cell: <kbd>cmd</kbd> + <kbd>enter</kbd>  
  to delete a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>D</kbd>  
* Go to https://colab.research.google.com and create a new notebook.
---
* Create a new cell, enter: `someint=10` and run it  
  `someint` is a **variable**.  
  The `=` sign is an **assignment**.  
  You can assign a number or a text to the variable.  
  It is called the variable's **value** or **state**  
  The number or text assigned to a variable is the  of that variable.  
  We say: 'someint' variable is assigned a value of 10  
  or: the state of variable 'someint' is 10.
* Crate a new cell, enter: `somestring="10"` and run it
* Create a new cell, enter `somefloat=10.0` and run it  
---
* Create 3 new cells, write the following code and execute:
* cell 1: `type(some_int)`
* cell 2: `type(some_string)`
* cell 3: `type(some_float))`  
  Notice we used a new function named **type**  
  type() is a python function returning type of its argument  
  int stands for integer number  
  str stands for string of characters  
  float stands for floating point number  
---
* Create a new cell, enter: `type(some_int+1)` and run  
  notice:  
  when you run a cell with variable assingment, those variables can be accessed in all following cells.
* Create a new cell, enter: `type(some_int-1)` and run  
* Create a new cell, enter: `type(some_int*2)` and run  
* Create a new cell, enter: `type(some_int*2.0)` and run  
* Create a new cell, enter: `type(some_int/2)` and run  
  Question: Why is the type of last 2 cells float?  
  Answer:  
  Python interprets expressions and assigns them the most suitable type.  
  Result of multiplying an integer by float is assumed to be float.
  Programming languages with such feature are called **dynamically typed**
---
* Create a new cell, enter: `some_int/0` and run  
  Remember:  
  When unexpected or illegal operation is executed, python will **throw an exception**  
  Well designed exception should clearly indicate what went wrong.  
  You can define and throw custom exceptions, we will explore it in further chapters.
* Create a new cell, enter: `some_string + 1` and run
  Question: What is the reason for the exception you see?

**Congratulations, you found out about variables, types and exceptions!**

    
