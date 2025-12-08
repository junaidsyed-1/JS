# This is the begining of Week-02, We will learn JavaScript Foundations (Deepening core skills).
- By the end of this week, you will feel confident with real JS logic, functions, arrays, loops, and you’ll write your first small project.

## Topics covered this week
- Day-01 Functions Deep Dive
    - Topics
        - Function declarations vs expressions
        - Arrow functions
        - Parameters vs arguments
        - Default parameters
        - Return values
    - Tasks
        - Re-write 5 small problems using both normal function + arrow function
    - Examples:
        - Add two numbers
        - Check even/odd
        - Convert minutes to seconds
        - Return the largest of two numbers
        - Create a function to greet a person

- Day-02 Arrays
    - Topics
        - Creating arrays
        - push(), pop(), shift(), unshift()
        - includes(), indexOf()
        - slice() vs splice()
    - Tasks
        - Build an array of 10 numbers
        - Write functions:
        - return sum of array
        - return max value
        - remove duplicates
        - reverse array (without .reverse)

- Day-03 Loops + Logical Thinking
    - Topics
        - for
        - while
        - for...of
        - Breaking/continuing loops

- Day-04 Objects (Very Important)
    - Topics
        - Create objects
        - Access data (dot + bracket)
        - Add/remove properties
        - Loop through object

- Day-05 Mini Project
    - Build a small project using everything from this week
    - Features:
        - Add new students
        - Remove students
        - Display all students
        - Count how many students
        - Check if student exists
    - Use:
        - arrays
        - objects
        - functions
        - loops

- Day-06 Basic String Manipulation
    - Topics
        - toUpperCase()
        - toLowerCase()
        - trim()
        - split()
        - join()
        - replace()
    - Tasks
        - Reverse a string
        - Count words
        - Check if a string is palindrome
        - Capitalize the first letter of every word in a sentence
        - Convert a sentence to camelCase

## Day-01
- Function Declarations VS Expressions
    - Function Declaration: is when we declare a function with syntax: function getValue(){}.
    - Function Expression: is when we decalre a function as an expression for instance let value = function(arg1){}.
- Arrow Functions
    - Arrow Functions is another way for creating functions, it is very simple and concise. The syntax is let func = (arg1,arg2) => expression;
    - Arrow Functions have no "this", if "this" is accessed it is taken from the outside.
- Parameter VS Arguments
    - Parameter is the name in the function definition which we pass to a function inside the paranthesis
    - Arguments are the actual values passed.
- Default parameters
    - We can pass default parameters to a function, if the parameter does not get any argument, we can have a default parameter for instance: 
    -   function showMessage(text) {
        if (text === undefined) { // if the parameter is missing
            text = 'empty message';
        }
        alert(text);
        }
- Return Values
    - A function can return a value, as soon as the function return it exits the function and stop executing further, we can also do an empty return.

## Day-02
- Push(): Add an element at the end of the Array.
- pop(): Remove an element from the end of an Array.
- shift(): Add an element in an Array at the begining.
- unShift(): Remove an element from the begining in Array.
- includes(): checks if any value of an element matches, and return a boolean
- indexof(): checks if any value in array matches and return the index of the element.
- splice(): splice is a method which can add,remove replace an element, it can do everything inside an Array. It modifies the acutall Array and does not create a copy.
- slice(): slice is a method which creates the copy of the transformed Array.

## Day-04
- What are Objects?
Objects are key-value containers where keys are string and value can be any data type,including their objects and functions. They are non-primitive data type.

- Accessing data
    - DOT notation: default when we know the property name at code time.
    - square Bracket notation: when key is dynamic or not a valid identifier.

## Day-06
#### We can not modify the acutal string using any method because the data type is primitive, which means that this data type can not be modified. All the methods creates a new string.
- toUpperCase(): it convert the text to upper case.
- toLowerCase(): This method converts the text to lower case.
- trim(): This method removes whitespace from both ends of the string and returns a new string, without modifying the original string.
- split(): This method split the string into an Array.
- join(): This methods joins the Array into the string.
- replace(): replace(pattern, replacement) => it returns a new string with one, some or all matches of a pattern replaced by replacement