# PRG101-Lab3
### Submission Details

In this lab, you will create four simple scripts. Write the scripts in GitHub codespaces. 
Please note that you will work on the lab during class hours and show your progress to the professor to receive the marks for the lab. If not completed, you can continue working on lab at home and submit a PDF file containing all screenshots showing your code and output in Blackboard before the due date.
Also carefully read the lab submission instructions given at the end of this file.

### Lab Objectives
- To be able to use data type List.
- To collect elements using lists
- To use the for loop for traversing lists
- To learn common functions and methods for processing lists
- To use lists with functions
- To work with tables of data- 

## INVESTIGATION : USING LISTS, LISTS OPERATIONS, LIST in FUNCTIONS, TABLE
A list in Python is an ordered collection of items that can be of different types. Lists are mutable, meaning you can change their content after creation.
In this Part you will be creating lists and performing basic operations on lists using list methods and built-in functions.
Lists are used to store data elements. Usually lists contain similar kind of data, but python does not restrict you from adding values of different data types in a list.


### lab3a.py
Write a Python program that generates a sequence of 20 random values between 0 and 99, stores them in a list, prints the sequence, sorts it, and prints the sorted sequence. Use the list sort method.

### lab3b.py
Write a function that reverses the sequence of elements in a list. For example, if you call the function with the list

1 4 9 16 9 7 4 9 11

then the list is changed to

11 9 4 7 9 16 9 4 1



### lab3c.py
### Creating lists and list concatenation
Lists are constructed with brackets [] and commas separating every element in the list. For example:
```Python
numbers=[1,2,3,4]
mixed_list=[1, "two", 4.5, True]
```
- Fill in the required fields in the comment section
- Create a variable of the type list called `mylist1` and save first three odd numbers (1,3,5) in it.
- Create a second variable of the type list and call it `mylist2`, save first three even numbers (0,2,4) in it.
- Create a third variable called `mylist`. This variable should contain all elements form mylist1 and mylist2. Remember you can use + to concatenate lists, just like we did for strings.
- Print the variable `mylist`.

### lab3d.py
### Using list methods to add and remove elements from a list 

- Fill in the required fields in the comment section.
- Create a variable `mylist` that conatins  first 6 natural numbers.
- Use the `append()` method and add a new element, number 7 in the variable `mylis`t. 
- Use the `inser()` method and insert the element 0 at index 0.
- Use the `pop()' method to remove the element from index 2.
- Print the variable `mylist`.
- Add another statement in the script to find the index of the element 6 and print `The element 6 is present at the index ---`

## lab3e.py
### Modifying a list and using the list in a loop
- Fill in the required fields in the comment section.
- Create a list variable called `students`. Add the following names in this list: Ama, Elina, Maija, Daniel, Ibrahim.
- Next change the element at index 1 and update this element with "Maggy".
- Now use a` for loop` and iterate over this list and print each element on a separate line. 

  
## lab3f.py
### Two Dimensional Lists
A great feature of of Python data structures is that they support *nesting*. This means we can have data structures within data structures. For example: A list inside a list.
A 2D list is a list where each element is itself a list. These inner lists represent rows, and the elements within them represent columns.

```Python
matrix = [
[1, 2, 3],
[4, 5, 6],
[7, 8, 9]
]

element = matrix[1][2]  # Output: 6
```
- Fill in the required fields in the comment section.
- Copy the above code in the file `lab3i.py`.
- Print the element `5` from this list. Specify the correct row and column.
- Print the element `2` from this list.
- Print the element `9` from this list.
- Use a for loop and print individual lists from this matrix. You need a single for loop. The output should be like this:
  ```python
  [1,2,3]
  [4,5,6]
  [7,8,9]
  ```
## lab3g.py
Write a program that reads values from standard input from user(using input function), stores the inputted values in a list, multiplies each element by 10, and prints the result in reverse order. 

## Lab 3 Sign-Off
- Submit the screenshots of each individual script, the screenshot must show your scripts and command line interface and output.
- The screenshot must also show your username on github codespaces.
- Make sure screenshots are not blurry, they should be easily readable.
- Please do not leave empty lines in your code, so that your script can fit in one screen.
- Submit individual screenshots of the following scripts on blackboard. If the screenshots do not correctly show the information mentioned above, you will need to re-do and resubmit lab with late penalty in effect.
    -lab3a.py
    - lab3b.py
    - lab3c.py
    - lab3d.py
    - lab3e.py
    - lab3f.py
    - lab3g.py


