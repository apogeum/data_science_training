 
---
Time to do some operations with our variables.  
* Run a new cell:
  ```
  someint+1
  ```  
* Run a new cell:
  ```
  somefloat+1
  ```  
* Run a new cell:
  ```
  someint + somefloat
  ```  
  The variables `someint` and `somefloat` are both **numeric types** so it is safe to perform operations like + or - with different typess.

---
* Create a new cell: `type(some_int+1)` and run  
  notice:  
  when you run a cell with variable assingment, those variables can be accessed in all following cells.
* Create a new cell: `type(some_int-1)` and run  
* Create a new cell: `type(some_int*2)` and run  
* Create a new cell: `type(some_int*2.0)` and run  
* Create a new cell: `type(some_int/2)` and run  
  Question: Why is the type of last 2 cells float?  
  Answer:  
  Python interprets expressions and assigns them the most suitable type.  
  Result of multiplying an integer by float is assumed to be float.
  Programming languages with such feature are called **dynamically typed**
---
* Create a new cell: `some_int/0` and run  
  Remember:  
  When unexpected or illegal operation is executed, python will **throw an exception**  
  Well designed exception should clearly indicate what went wrong.  
  You can define and throw custom exceptions, we will explore it in further chapters.
* Create a new cell, enter: `some_string + 1` and run
  Question: What is the reason for the exception you see?
