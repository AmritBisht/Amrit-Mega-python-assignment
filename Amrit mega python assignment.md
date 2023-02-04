
Q1. Why do we call Python as a general purpose and high-level programming language?

Ans: We call Python as a general purpose programming language because it is used in many popular fields 
     like machine learning, artificial intelligence, Data science etc. and it is called high level programming language
     as it is a programming language which is closely associated with human understanding, that is its syntax or way of
     writing is easily understandable




Q2. Why is Python called a dynamically typed language?

Ans: Python is called a dynamically typed language because in Python the type of a variable is determined at runtime 
     rather than at compile time. we don't have to specify the data type of a variable when we declare it and the type
     of a variable can change during the execution of the program. 




Q3. List some pros and cons of Python programming language?

Ans: Pros:-
     * Easy to Read, Learn and Write
     * Dynamically Typed
     * Free and Open-Source
     * Vast Libraries Support
     * Improved Productivity
   
     Cons:- 
     * Not Memory Efficient
     * Runtime Errors
     * Difficult to test 
     * Speed limitations



Q4. In what all domains can we use Python?

Ans: Data engineering, Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting,
     Networking, Game Development to Web Development.





Q5. What are variable and how can we declare them?

Ans: Variables are used to store information to be referenced and manipulated in a computer program.
     We can declare it as:- 
     ----------------------
     Var = "Ineuron"
     ----------------------





Q6. How can we take an input from the user in Python?

Ans: We can take it as:-
     ----------------------
     inp = input("Give your input: ")
     print(inp)
     ---------------------- 





Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans: Default datatype is String input function first takes the input from the user and converts it into a string.

 



Q8. What is type casting?

Ans: Type Casting is the method to convert the variable data type into a certain data type in order to the operation
     required to be performed by users.





Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans: Yes we can take more than one input from the user using single input() by using split function 

     ---------------------
     input().split(separator, maxsplit)
     ---------------------





Q10. What are keywords?

Ans: In Python keywords are special reserved words that have specific meanings and purposes and can't be used 
     for anything but those specific purposes.





Q11. Can we use keywords as a variable? Support your answer with reason.

Ans: We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define
     the syntax and structure of the Python language. All the keywords except True , False and None are in lowercase 
     and they must be written as they are.






Q12. What is indentation? What's the use of indentaion in Python?

Ans: Python indentation is a way of telling the Python interpreter that a series of statements belong to a particular 
     block of code.




Q13. How can we throw some output in Python?

Ans: We can get output in python by print() function it prints the message to the screen or any other standard output device.





Q14. What are operators in Python?

Ans: Operators are used to perform operations on variables and values. python divides the operators in the following groups:
     Arithmetic operators
     Assignment operators
     Comparison operators
     Logical operators




Q15. What is difference between / and // operators?

Ans: / is regular division and return float numeric datatype and // is floor division return int numeric datatype.




Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

```



Ans: ---------------
     print(iNeuron * 5)
     ---------------




Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans: ------------
     num = int(input("enter numer : "))
     if num % 2 == 0 :
        print(num,"is even number")
     else :
        print(num,"is odd number") 
     ------------



   
Q18. What are boolean operator?

Ans: Boolean Operators are those that result in the Boolean values of True and False. There are two types of operators in 
     python that return boolean values that are Logical operators and Comparison operators.



Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans: 1
     0
     False
     1





Q20. What are conditional statements in Python?

Ans: Conditional Statement in Python perform different computations or actions depending on whether a specific Boolean 
     constraint evaluates to true or false. python has 3 Conditional Statements :-

     * if statement
     * if-else statement
     * if-elif-else ladder





Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans: 'if' condition makes a decision based on whether the condition is true or not. If the condition is true, it prints 
     out the indented expression. If the condition is false, it skips printing the indented expression.
     'else' is use when the beginning of an if-else statement operates similar to a simple if statement however, if the condition is false, 
     instead of printing nothing, the indented expression under 'else' will be printed.
     When you run into a situation where you have several conditions, you can place as many 'elif' conditions as necessary between the if 
     condition and the else condition






Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans: ------------------
     age = int(input("I am : "))
     if age > 18:
        print("I can vote")
     else:
        print("I can't vote")


     --------------------


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans: ----------------------
     numbers = [12, 75, 150, 180, 145, 525, 50]
     a = 0
     for i in numbers:
         if i % 2 == 0 :
            a += i 
     print(a)
     -----------------------





Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans : ----------------------
      a = int(input("first num :"))
      b = int(input("second num :"))
      c = int(input("third num :"))

      if a > b :
         if a > c :
            print(a, "greatest number")
      elif a < b :
           if b < c :
              print(c, "greatest number" )  
           else : 
              print(b, "greatest number")      
       -------------------------





Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50] 
```


Ans: ---------------------
     numbers = [12, 75, 150, 180, 145, 525, 50]
     a = []
     for i in numbers:
         if i > 150:
            if i > 500:
               break
            continue
         elif i % 5 == 0:
              a.append(i)        
     print(a)
    ----------------------- 



Q26. What is a string? How can we declare string in Python?

Ans: A string is a data structure in Python that represents a sequence of characters. 
     It is an immutable data type, meaning that once you have created a string, you cannot change it.
     We can decalre string by either using single quote or dounle quote
     
     Str = "Namaste" or Str = 'Namaste'




Q27. How can we access the string using its index?

Ans: Indexing allows us to access individual characters in a string directly by using a numeric value. String indexing is zero-based
     the first character in the string has index 0, the next is 1, and so on. 
     We can acces the using as:

     Str = "Namaste"
     str[0:7]


Q28. Write a code to get the desired output of the following

     string = "Big Data iNeuron"
     desired_output = "iNeuron"

Ans: ------------------------

     String = "Big Data iNeuron"
     print(String[9:16])
 
     -------------------------




Q29. Write a code to get the desired output of the following

    string = "Big Data iNeuron"
    desired_output = "norueNi"
 
Ans: ------------------------

     string = "Big Data iNeuron"
     print(string[-1:-8:-1])
 
     ------------------------- 




Q30. Resverse the string given in the above question.

Ans: ------------------------

     string = "Big Data iNeuron"
     print(string[-1::-1])
 
     ------------------------- 


Q31. How can you delete entire string at once?

Ans: we can delete entire string as :
     ------------------------

     string = "Big Data iNeuron"
    
     Del string
 
     ------------------------- 



Q32. What is escape sequence?

Ans: Escape sequences allow us to include special characters in strings. 





Q33. How can you print the below string?

Ans: ------------------------

     Str = 'iNeuron\'s Big Data Course'
   
     print(Str)
 
     ------------------------- 




Q34. What is a list in Python?

Ans: A list in Python is used to store the sequence of various types of data. A list can be defined as a collection of 
     values or items of different types. Python lists are mutable type which implies that we may modify its element after it has been formed. 




Q36. How can we access the elements in a list?

Ans: We can access values in lists by using the square brackets for slicing along with the index or indices to obtain value available at that index.




Q37. Write a code to access the word "iNeuron" from the given list.

Ans: ------------------------

    lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]

    print(lst[4][2])
 
     ------------------------- 



Q38. Take a list as an input from the user and find the length of the list.

Ans: --------------------------
    inpt = list(input("Enter a list element separated by space ").split())
    
    print(len(inpt))
    ------------------------------



Q39. Add the word "Big" in the 3rd index of the given list.

Ans: -----------------

     lst = ["Welcome", "to", "Data", "course"]
     lst.insert(2,"big")
     print(lst)
     

    ------------------------------




Q40. What is a tuple? How is it different from list?

Ans: Tuples are sequence data type containing elements of different data types.It comes in handy when storing a collection of items, especially
     if you want those items to be unchanging. The primary difference between tuples and lists is that tuples are immutable as opposed to lists 
     which are mutable. Therefore, it is possible to change a list but not a tuple.




Q41. How can you create a tuple in Python?

Ans: A tuple is created by placing all the items (elements) inside parentheses (), separated by commas. 
    
    tuple = ()





Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

Ans : No we can't add elements to a tuple because of their immutable property.





Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

Ans : No we can't append two tuple because of their immutable property.




Q44. Take a tuple as an input and print the count of elements in it.

Ans: -----------------

     tuple = tuple(input('Enter space separated words: ').split())

     print(len(tuple))
     

    ------------------------------



Q45. What are sets in Python?

Ans: Sets are used to store multiple items in a single variable. A set is a collection which is unordered, unchangeable and unindexed.

    



Q46. How can you create a set?

Ans: we can create set by the set() function without any argument.  using curly braces and add objects individually
   
    empty_set = set()





Q47. Create a set and add "iNeuron" in your set.

Ans:--------------------- 
   
    a = set()
    a.add("iNeuron")
    print(a)

  -----------------------




Q48. Try to add multiple values using add() function.

Ans: we cannot add mutliple value using single add() function as add() takes exactly one argument.





Q49. How is update() different from add()?

Ans: We use add() method to add single value to a set and we use update() method to add sequence values to a set. 





Q50. What is clear() in sets?

Ans: The clear() method removes all elements in a set.





Q51. What is frozen set?

Ans: Frozen set are just an immutable set .




Q52. How is frozen set different from set?

Ans: Elements of the frozen set remain the same after creation.  




Q53. What is union() in sets? Explain via code.

Ans: The Python set union() method returns a new set with distinct elements from all the sets.
     ------------------------------
     A = {2, 3, 5}
     B = {1, 3, 5}

     
    print('A U B = ', A | B)


    # Output: A U B =  {1, 2, 3, 5}

     --------------------------------




Q54. What is intersection() in sets? Explain via code.

Ans: The intersection() method returns a new set with elements that are common to all sets.
    ------------------------------
     A = {2, 3, 5}
     B = {1, 3, 5}

     
    print('A U B = ', A & B)


    # Output: A U B =  {1, 2, 3, 5}

     --------------------------------





Q55. What is dictionary ibn Python?

Ans: A dictionary in Python is a collection of key-value pairs. The dictionary keys must be unique.



Q56. How is dictionary different from all other data structures.

Ans: A dictionary is associated with a set of keys and each key has a single associated value. When presented 
     with a key, the dictionary will simply return the associated value.



Q57. How can we delare a dictionary in Python?

Ans: Dictionary is listed in curly brackets, inside these curly brackets, keys and values are declared. Each key 
     is separated from its value by a colon (:), while commas separate each element.

     Dict = { 'Amrit': 18, }




Q58. What will the output of the following?
     
      var = {}
     print(type(var))

Ans: <class dict>



Q59. How can we add an element in a dictionary?

Ans: The syntax for adding items to a dictionary is the same as the syntax we used when updating an item. The only difference here
     is that the index key will include the name of the new key to be created and its corresponding value.




Q60. Create a dictionary and access all the values in that dictionary.

Ans: --------------------------------------
    
     dict = {
            "name": "Amrit",
            "course": "Big data",
            "language" : "Python"
              }

     print(dict)

    ----------------------------------------





Q61. Create a nested dictionary and access all the element in the inner dictionary.

Ans: ---------------------------------------
     people = {1: {'name': 'Amrit', 'course': 'Big data', 'sex': 'Male'},
               2: {'name': 'sidharth', 'course': 'web devlopment', 'sex': 'Male'}}
     a =people[1]
     b =people[2]
     print(a)
     print(b)
    -------------------------------------------




Q62. What is the use of get() function?

Ans: The get() function returns the value of the item with the specified key.




Q63. What is the use of items() function?

Ans: The items() function returns a view object. The view object contains the key-value pairs of the dictionary, as tuples in a list.




Q64. What is the use of pop() function?

Ans: The pop() function removes the element at the specified position.




Q65. What is the use of popitems() function?

Ans: The popitem() function removes the item that was last inserted into the dictionary.



Q66. What is the use of keys() function?

Ans: The keys() function returns a view object. The view object contains the keys of the dictionary, as a list.




Q67. What is the use of values() function?

Ans: The values() function returns a view object. The view object contains the values of the dictionary, as a list.




Q68. What are loops in Python?

Ans: loop is an instruction that repeats multiple times as long as some condition is met.




Q69. How many type of loop are there in Python?

Ans: Python has two types of Loops.

    1	for loop	Is an iterator based loop, which steps through the items of iterable objects like lists, tuples, string and executes a piece of 
                        code repeatedly for a number of times, based on the number of items in that iterable object.

    2	while loop	Executes a block of statements repeatedly as long as the condition is TRUE 




Q70. What is the difference between for and while loops?

Ans: A for loop is a single-line command that will be executed repeatedly. While loops can be single-lined or contain multiple commands for a single condition.




Q71. What is the use of continue statement?

Ans: Continue Statement skips the execution of the program block from after the continue statement and forces the control to start the next iteration.




Q72. What is the use of break statement?

Ans: Break Statement is used to terminate the execution of the loop. 
 


Q73. What is the use of pass statement?

Ans: The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid getting an error when 
     empty code is not allowed.



Q74. What is the use of range() function?

ANs: The Python range() function returns a sequence of numbers, in a given range.



Q75. How can you loop over a dictionary?

Ans: we can loop through a dictionary by using a for loop. When looping through a dictionary, the return value are the keys of the dictionary, but there 
     are methods to return the values as well.




Q76. Write a Python program to find the factorial of a given number.

Ans: ------------------------------------
     a =  int(input('enter number :'))
     x = 1
    for i in range(1,a+1):
        x = i*x
    print("factorial of",a,"is",x)    
    -------------------------------------------




Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

Ans: ---------------------------------------------
     p = int(input("principal :"))
     r = int(input("rate :"))
     t = int(input("time :"))
     x = (p*r*t)/100
     print("Simple interest is :",x,"rs")
     ---------------------------------------



Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Ans: -----------------------------------
     p = int(input("principal :"))
     r = int(input("rate :"))
     t = int(input("time :"))
     x = p*((1+r/100))**t
     ci = x - p
     print("Compund interest is :",round(ci,2),"rs")
     ---------------------------------------



Q79. Write a Python program to check if a number is prime or not.

Ans: -----------------------------------------
     x = int(input("enter your number :"))
     if x == 0 :
        print(x,"is whole number")
     elif x % 2 == 0 :
        print(x,"is prime number")
     else: 
        print(x,"is odd number")
     ----------------------------------------------


Q80. Write a Python program to check Armstrong Number.

Ans: ----------------------------------------------
     n = int(input('number:'))
     sum = 0 
     x = len(str(n))
     copy_n = n
     while n > 0:
          digit = n % 10
          z = digit**x
          sum += z
          n = n // 10
     if copy_n == sum:
        print('armstrong')
     else: 
        print('not a armstrong')
    ---------------------------------------------------



Q81. Write a Python program to find the n-th Fibonacci Number.

Ans:-----------------------------------------
        def fibonacci(n):
	a = 0
	b = 1
	
	if n < 0:
	   print("Incorrect input")
		
	elif n == 0:
	     return a
	
	
	elif n == 1:
	     return b
	
        else:
	    for i in range(1, n):
		c = a + b
		a = b
		b = c
	    return b
      -------------------------------------




Q82. Write a Python program to interchange the first and last element in a list.

Ans: ----------------------------------------------
     list = input('enter the list element seprated by space ').split()
     print(list)
     length = len(list)
     a = list[0]
     b = list[(length-1)]
     list[0] = b
     list[(length-1)] = a
     print(list)
     ------------------------------------------------



Q83. Write a Python program to swap two elements in a list.

Ans: --------------------------------------------------
     list = input('enter the list element seprated by space ').split()
     print(list)
     x = int(input('enter the first positon'))
     y = int(input('enter the second positon'))
     a = list[x]
     b = list[(y)]
     list[x] = b
     list[(y)] = a
     print(list)
     ---------------------------------------------------




Q84. Write a Python program to find N largest element from a list.     

Ans: -----------------------------------------------------------------
     lst = input('enter the list element seprated by space ').split()
     n = int(input("enter the Nth term:"))
     list = []
     for j in range(1,n+1):
         max = 0    
         for i in lst:
             if int(i) > int(max) :
                max = i
         lst.remove(max)  
         list.append(max)    
     print(list)
     ---------------------------------------------------------------------------




Q85. Write a Python program to find cumulative sum of a list.

Ans: --------------------------------------------
     lst = input('enter the list element seprated by space ').split()
     print(lst)
     a = 0
     for i in lst:
         a = int(a) + int(i)
     print(a)
     --------------------------------------------------



Q86. Write a Python program to check if a string is palindrome or not.

Ans: --------------------------------------------
     num = int(input('enter the number '))
     temp_num = num
     a = 0
     while num > 0:
           digit = num % 10 
           a = a * 10 + digit
           num = num // 10
     if temp_num == a:
        print(a,'is a palindrome number')
     else:
        print(a,'not a palindrome number')
     --------------------------------------------



Q87. Write a Python program to remove i'th element from a string.

Ans: ------------------------------------------------
     str = input('enter the string: ')
     pos = int(input('the i\'th element u want to remove :' ))
     n = pos - int(1)
     print(str)
     str = str[:n] + str[(n+1):]
     print(str)
     ---------------------------------------------------




Q88. Write a Python program to check if a substring is present in a given string.

Ans: -----------------------------------------------
     str = input('enter the String: ')
     sbstr = input('enter the Substring: ')
     if sbstr in str:
        print('Yes! it is present in the string')
     else: 
        print('No! it is not present')    
    -------------------------------------------------



Q89. Write a Python program to find words which are greater than given length k.

Ans: -------------------------------------------------------
     str = input('enter the sentence: ')
     lst = str.split() 
     list = []
     k = int(input("the length be : "))
     for i in lst:
         if len(i) > k :
            list.append(i)      
     x = ""  
     for i in list:
         x = x + ' ' + i
     print(x)    
    ----------------------------------------------------------



Q90. Write a Python program to extract unquire dictionary values.

Ans: ------------------------------------------------------------
     x = { 'A' : [1, 3, 5, 4], 'B' : [4, 6, 8, 10], 'C' : [6, 12, 4 ,8], 'D' : [5, 7, 2] }
     a =[]
     for i in x:
         a.extend(x[i])
     print(a)
     y = list(set(a))
     print(sorted(y))
     -----------------------------------------------------------------



Q91. Write a Python program to merge two dictionary.

Ans: -----------------------------------------------------------------
     dict_1 = {1: 'a', 2: 'b'}
     dict_2 = {2: 'c', 4: 'd'}

     dict_3 = dict_2.copy()
     dict_3.update(dict_1)
     print(dict_3)   
     -------------------------------------------------------



Q92. Write a Python program to convert a list of tuples into dictionary.

     Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
     Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}

Ans: ------------------------------------------------------------

     Input = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
     diction = dict()
     for i,n in Input:
         diction.setdefault(i,[]).append(n)
     print(diction) 
   
     ---------------------------------------------------



Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

     Input: list = [9, 5, 6]
     Output: [(9, 729), (5, 125), (6, 216)]

Ans: ----------------------------------------------------------
     list = [9, 5, 6]
     lst = [(i,i**3) for i in list]
     print(lst)
     --------------------------------------------------



Q94. Write a Python program to get all combinations of 2 tuples.

     Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
     Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]


Ans: --------------------------------------------------------
     tuple1 = (7, 2)
     tuple2 = (7, 8)
     result =  [(x, y) for x in tuple1 for y in tuple2]
     result = result +  [(x, y) for x in tuple2 for y in tuple1]
     print(result)
     -------------------------------------------------------




Q95. Write a Python program to sort a list of tuples by second item.
 
     Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
     Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Ans: ----------------------------------------------------
     tupleList = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
     print("Unordered list : ", str(tupleList))
     tupleList.sort(key = lambda val: val[1]) 
     print("Sorted List : ", str(tupleList))
     ----------------------------------------------------




Q96. Write a python program to print below pattern.

     * 
     * * 
     * * * 
     * * * * 
     * * * * * 

Ans: ----------------------------------------
    for i in range(5):
         for j in range(i+1):
             print('*',end='')
         print()    
     ------------------------------------------




Q97. Write a python program to print below pattern.

         *
        **
       ***
      ****
     *****

Ans: ------------------------------------------------
     for i in range(1,6):
         for j in range(1,6):
             if (j <= 5-i):
                 print(' ',end='')
             else :
                 print('*',end='')
         print()    
     ------------------------------------------





Q98. Write a python program to print below pattern.

         * 
        * * 
       * * * 
      * * * * 
     * * * * * 

Ans: ----------------------------------------------
     rows = 5 
     k = 0
     for i in range(1, rows+1):
        for space in range(1, (rows-i)+1):
            print(end="  ")
   
        while k!=(2*i-1):
              print("* ", end="")
              k += 1
   
        k = 0
        print()
    --------------------------------------------




Q99. Write a python program to print below pattern.

     1 
     1 2 
     1 2 3 
     1 2 3 4 
     1 2 3 4 5
    
Ans: ----------------------------------------
     for i in range(1,6):
         for j in range(1,i+1):
             print('*',end='')
         print()    
     ------------------------------------------   




Q100. Write a python program to print below pattern.

      A 
      B B 
      C C C 
      D D D D 
      E E E E E 

Ans: ----------------------------------------
     for i in range(1,6):
         for j in range(1,i+1):
             print(chr(j+64),end='')
         print()    
     ------------------------------------------   
