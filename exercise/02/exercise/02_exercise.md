# f-strings

When you try to mix data types e.g. string and int in `print()`, things get tricky.

for e.g. if you try to print :
```
first_name = "your name"
my_integer = 8
print(first_name + ' is '+ my_integer+ ' years old')
```

**WHY ?** Because you are trying to mix data types - string with an integer. Just the `print()` statement is not *smart* enough to know this !

With **f-strings**, you can simply surround the objects in the `print()` function with `{}` and print will take care of handling the data types ! How cool is that !!

Now you can just do (in our previous example) as 

```
print(f"{first_name} is {my_integer} years old.")

# the variables are surrounded by {} (squible or curly brackets)
```
f-strings are intelligent enough to figure out and handle the data types and you no longer need to use `+` signs !

## Problem 1:

  use `f-strings` to print for below objects 

  - year = 2014
  - month = "December"
  - name = "Lucky"

  The sentence to print :

  `Lucky was born in December 2014.`
  
## Problem 2:
  You go to a grocery store and purchase 3 items 
   - item1 is apples, 
   - item2 is bananas and 
   - item3 is avacados 

  print below sentence using `f-strings`
  
  `At the grocery store, I bought some apples,bananas and avacados` 
  
## Problem 3:
  In the above problem, add quantities of each item
  
   - item1_quantity = 5
   - item2_quantity = 10
   - item3_quantity = 12
   
   print below sentence using `f-strings`
   
   `At grocery store, I bought 5 apples, 10 bananas and 12 avacados. I got total 27 items from grocery store !`
   
   Hint : use a total_items variable to add the quantities that you purchased.
   
## Problem 4: 
   we learned to day that you you can use `input` to ask and wait for user to input some data. e.g.
   
   `first_name = input("what is your first name?") `
   
   The above will wait for the user to input their first name and then store that in `first_name` variable.
   
   with that in mind, write a program that takes 2 numbers as input and stores them in 
   number1 and number2 variables. Then using `f-strings` print 
   
      `variable = int(input("provide 1st number"))   # this will store the number as "integer" (see int that we are using) in variable
   
   - The addition of the 2 numbers that you provided is ____
   - The subtraction of the 2 numbers that you provided is ____
   - The multiplication of the 2 numbers that you provided is ____

## Problem 5:
   write a program with below variables  
   ```
    language = 'Python'
    rank = 1
    who = 'all students'
    kids_age = 7
    teacher_surname = 'Shah'
   ```
   The output should be 
   
   ```
   Python is the world no 1 programming language, all students should start learning it from age 7 years old.
   And they all learn Python with Teacher Shah.
   all students enjoy learning Python, as Python is quite fun, and Teacher Shah is quite fun.
   ```
   
  
