*Remember:*  
*If you are using Windows, use <kbd>ctrl</kbd> key instead of <kbd>cmd</kbd> key*  
*To create a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>C</kbd>*  
*To run a cell: <kbd>cmd</kbd> + <kbd>enter</kbd>*  
*To delete a cell: <kbd>cmd</kbd> + <kbd>M</kbd> then <kbd>D</kbd>*  
*Unless specified otherwise, run each instruction in a **new cell***

---
* Go to https://colab.research.google.com and create a new notebook.
---
* run 
```max(2,1,5,4,3)```  
Question: what do you think `max()` function does?
* run  
```help(max)```  
  `help()` is a python function that explains the meaning of the function passed as an argument.  
  Notice that until now you were only passing variables or values to function.  
  You have just learned that you can pass one function as an argument of another.  
  When you pass a funtion as an argument, you just use its name without brackets, e.g. `help(print)`  
  It will come very useful in future exercises.
* Try to guess a function that finds minimum of `2,1,5,4,3` and run it
* verify your guess with the use of `help()` function
---
* run ```abs(10)```
* run ```abs(-10)```
* run ```abs(0)```
* try to guess what `abs()` is doing and then use `help()` to confirm
---
* run ```pow(2,3)```
* run ```pow(3,2)```
* use `help()` to find out what `pow()` is doing
* try to use `pow()` to calculate square root of 1089
* hint: squareroot is often expressed as the power of `1/2``
* an inverse of number n is 1/n. Express inverse of 5 using only `pow()` function. 
  hint: 1/x = x<sup>-1</sup>
---
* run `round(2)```
* run ```round(2.2)```
* run ```round(2.5)```
* run ```round(2.6)```
* run ```round(0.123456789, 1)```
* run ```round(0.123456789, 2)```
* round the number `0.123456789` to 6 decimal places
---
* run ```str(10)```  
  Notice: words enclosed in `"double quotes"` represent **literals of type String**  
  A literal is a value without a name
* run ```str(10.0)```
* guess what `str()` is doing and then use `help()` to confirm
---
* run ```int("10")```  
  Notice: whole numbers written without period `.` sign represent literals of type Int
* run ```int("10.0")```  
  Question: why do we see the exception?
  Answer: python sees the `.` and assumes there can be fractional part,  
  and decides it is not safe to treat this number as integer.
---
* run ```float("10")```  
  Notice: numbers written with period `.` separating whole and fractional part represent literals of type Float
* run ```float("10.1")```
* run ```float("10,0")```  
  Question: why do we see the exception?
  Answer:
---
* run ```bool("True")```  
  Notice: True and False (without quotations) are python literals to express 2 possible states of type **bool**
* run ```bool("true")```
  Important: bool is a function to transform other types to boolean.  
* run ```bool("false")```
  Important: `bool()` has certain assumptions on what does it mean that some type is false or true.  
  For example it treats any non-empty String as true.
  Those assumptions are not always intuitive, so let us test them.
* try to apply `bool()` function to the following values: `"tRuE", " ", "", 1, -1, 0, 1.1, -1.1, 0.0, None`
---
* run ```type(None)```
  Important: `None` is a python literal for a very special type called NoneType.  
  This type only has one valid value: `None`.  
  You will find out about usefulness of this type in further exercises.  
**Congratulations, you have found out about a lot of important python built-in functions!**
