*Remember:*  
*If you are using Windows, use <kbd>ctrl</kbd> key instead of <kbd>cmd</kbd> key*  
*To create a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>C</kbd>*  
*To run a cell: <kbd>cmd</kbd> + <kbd>enter</kbd>*  
*To delete a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>D</kbd>*  

---
* Go to https://colab.research.google.com and create a new notebook.
---
Let's get started with variables  
* Create a new cell
* Enter:  
  ```
  someint=10
  print(someint)
  ```  
* Run the cell, the output should look as follows:  
```
10
```  
 The `someint` is a **variable**.  
 The `=` sign is an **assignment**.  
  Variables have their corresponding **values**.  
  
  The variable `someint` is assigned a value of 10.  
  We can also say that the **state** of variable `someint` is 10.  
  
  
Let's try assigning some more variables.  
* Run a new cell:  
```
somestring="10"
print(somestring)
```  
* Run a new cell:  
```
somefloat=10.0
print(somefloat)
```  
---
Now let's learn about types  
* Create a cell `type(some_int)`
* Create a cell `type(some_string)` and run
* Create a cell `type(some_float))` and run  
  Notice we used a new function named **type**  
  type() is a python function returning type of its argument  
  int stands for integer number  
  str stands for string of characters  
  float stands for floating point number  
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

**Congratulations, you found out about variables, types and exceptions!**

    
