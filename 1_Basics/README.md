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
 Assignment operation does not result in any output.  
 That is why we use `print()` function to be able to view our assigned value.
  
Let's try defining some more variables:  
* Run a new cell:  
  ```
  somestring="ten"
  print(somestring)
  ```  
  Output:  
  ```
  'ten'
  ```  
  
* Run a new cell:  
  ```
  somefloat=10.0
  print(somefloat)
  ```  
  Output:  
  ```
  10.0
  ```
---
Now let's learn about types  
* Run a new cell:  
  ```
  type(someint)
  ```  
  Output:  
  ```
  int
  ```  
  We have just made a **function** call, which you may recall from previous chapter.  
  Function call has a form of `function_name(argument1, argument 2, ..., argumentN)`.  
  We have used a built-in function named **type**.  
  We passed previously defined `someint` variable as an **argument** to this function.  
  This function tells us what is the type of our argument.   
  In this case the function returns `int` which stands for **integer type**.  
  Integer type represents whole numbers e.g. 1, 10, 0, -115.  
  
Let's try another type.  
* Run a new cell:  
  ```
  type(somestring)
  ```  
  Output:  
  ```
  str
  ```  
  In this case the function returns `str` which stands for **string of characters**.  
  String type represents a sequence of characters (text) e.g. "hello", "ten", "This is a fox. Hello fox!"  
  
* Run a new cell:  
  ```
  type(somefloat)
  ```  
  Output:  
  ```
  float
  ```  
  In this case the function returns `float` which stands for **floating point number**.  
  Float type represents a number that has a decimal place, e.g. 1.1, 2.0, -7.0002, 0.001.
 
**Congratulations, you found out about defining variables and basic types!**

    
