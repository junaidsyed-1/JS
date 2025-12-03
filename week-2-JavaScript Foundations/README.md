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