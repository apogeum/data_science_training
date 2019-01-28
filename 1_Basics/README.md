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
* Run the cell and the output should be:  
  ```
  10
  ```  
 The `someint` is our **variable**.  
 The `=` symbol is called **assignment**.  
 After running the cell, the variable `someint` has been assigned a **value** of 10.    
  
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
* Run a new cell:  
  ```
  type(someint)
  ```  
  You may recall from previous chapter that we have just made a function call.
  Function calls have a form `function_name(argument1, argument 2, ..., argumentN)`.  
  We have used a python function named **type**.  
  We passed `someint` variable as an argument to the function.  
  The **type** function tells us what is the type of the variable.   
  Int stands for integer number.  
* Run a new cell:  
  ```
  type(somestring)
  ```  
  Str means **string of characters**.  
* Run a new cell:  
  ```
  type(somefloat)
  ```  
  Float means **floating point number**.  
---
Time to do some operations with our variables.  
* Run a new cell:
```
someint+1
```  

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

    
