*Remember:*  
*If you are using Windows, use <kbd>ctrl</kbd> key instead of <kbd>cmd</kbd> key*  
*To create a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>C</kbd>*  
*To run a cell: <kbd>cmd</kbd> + <kbd>enter</kbd>*  
*To delete a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>D</kbd>*  
*Unless specified otherwise, run each instruction in a **new cell***

---
* Go to https://colab.research.google.com and create a new notebook.

---
In this chapter we will learn about operations on basic types.  
* Run the code in one cell:  
  ```
  zero=0
  first=9
  second=2.0
  third="fox"
  ```  
  You already know that we have just defined some variables.  
* Run:
  ```
  first+1
  ```  
  Output:  
  ```10```
* Run:
  ```
  second+1
  ```  
  Output:  
  ```3.0```
* Run:
  ```
  first + second
  ```  
  Output:  
  ```11.0```
* Run:
  ```
  first - second
  ```  
  Output:  
  ```7.0```  
  Variables `first` and `second` are both **numeric types** so we can mix them in operations, like addition, subtraction, multiplication or division.
---
* Run:
  ```
  first * second
  ```
  Question: What is the type of the result of `first * second`?  
  Answer: It is float. Python knows that the result of this operation might not be an integer (whole number).  
  That is why python decides it is safer to assume the result is always float.  
  Result of mathematical operations between integer and float is assumed to be float.
* Run:
  ```
  10/(6-1)
  ```  
  Notice that here we did not use any variables in the code. We performed numeric operations on **values**.
* Run:
  ```
  result = 2*(3.5+first)/(5.1-6)
  print(result)
  ```  
  Notice that we can assign the result of an operation to a variable.  
---
* Run:
  ```
  first / zero
  ```  
  Output:  
  ```
  ZeroDivisionError Traceback (most recent call last)
  <ipython-input-4-7a5050487faa> in <module>()
  ----> 1 9/0
  ZeroDivisionError: division by zero
  ```  
  Question: Can you tell what did we do wrong?
  **Remember:** When unexpected or illegal operation is executed, python will **throw an exception**  
  Well designed exception should clearly indicate what went wrong.  
---
Now let's find out what operations can we do on strings.  
* Run:
  ```
  "hello" + " " + third + "!"
  ```  
  Looks like we can add strings together. This operation is usually called **concatenation**.  
How about mixing strings with other types in addition?  
* Run:
  ```
  third + 1
  ```
  Question: What is the reason for the exception you see?  
---
* Task: Only one of below operations is allowed.  
  Try to guess and then execute each line in a new cell to see if you were right.
  ```
  "haha" - 10
  "haha" / 10
  "haha" * 10
  ```
---
  **Congratulations. _encouraging message_**
  
