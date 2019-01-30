*Remember:*  
*If you are using Windows, use <kbd>ctrl</kbd> key instead of <kbd>cmd</kbd> key*  
*To create a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>C</kbd>*  
*To run a cell: <kbd>cmd</kbd> + <kbd>enter</kbd>*  
*To delete a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>D</kbd>*  
*Unless specified otherwise, run each instruction in a **new cell***

---
* Go to https://colab.research.google.com and create a new notebook.

---
In this chapter we will learn about basic operations on variables.  
* Run the two instructions in one cell:  
  ```
  first=10
  second=2.0
  third="fox"
  ```  
* Run:
  ```
  first+1
  ```  
* Run:
  ```
  second+1
  ```  
* Run:
  ```
  first + second
  ```
* Run:
  ```
  first - second
  ```
* Run:
  ```
  first * second
  ```
* Run:
  ```
  first / second
  ```
  Variables `first` and `second` are both **numeric types** so we can mix them in operations, like addition, subtraction, multiplication or division.

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
