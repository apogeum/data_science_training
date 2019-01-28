* run `thelist=[3,4,1,2]`  
  Important: you have just created your first variable of type list.  
  `thelist` is our name of the variable, it can be anything  
  `[3,4,1,2]` is a value of type List that contains 4 numbers in the exact order  
  
---
  Let us try how some of the python functions we learned work on lists.
* run `type(thelist)`
* run `max(thelist)`
* Think how to find a minimum element of the list
---
  There are some python functions that only work with container types.  
  Container types are the types that can contain other variables in them.  
  As you probably guessed, list is a container type.  
* run `len(thelist)`
* run `help(len)`
* run `sorted(thelist)`
* run `help(sorted)`
  As you see from the description, the default order of the result is ascending,  
  but it can be changed using 'reverse' argument.  
* run `sorted(thelist, reverse=True)`
---
* run `sum(thelist)`  
  `sum()` is a python function that return a sum of all elements of passed list.  
* run `sum([3,4,1,2])`  
  Important: in the code above, instead of passing a variable name to the function,  
  you are passing a literal value, you should prefer this construct if you are not  
  planning to use the list further in the code.
* Using the value passing technique, calculate the sum of numbers: 123, 456, 789
---
* run `thelist[0]`  
  Important: the above construct has a general form of `list_name[n]`  
  It returns the n'th element of the list. that 'n' is also called the **index**
  VERY IMPORTANT: list indexes in python start from 0.
* run `thelist[1]`
* run `thelist[3]`
* run `thelist[4]`
  Question: what is the reason for the exception you see?
  Answer: because list indexes start at 0, the only valid indexes for our list  
  are: 0, 1, 2, 3. Indexes 4 and above are out of bounds.
---
todo: list of other types
---
todo: show that strings behave like lists
