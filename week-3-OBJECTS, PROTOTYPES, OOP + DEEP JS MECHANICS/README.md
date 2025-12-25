# 🚀 This is the beginning of Week-03, In this week we will dive deep into OBJECTS, PROTOTYPES, OOP + DEEP JS MECHANICS
## 📌 Main Goal of Week 3
- To understand how JavaScript actually works under the hood, especially:
    - objects
    - reference types
    - prototype chain
    - constructor functions
    - classes
    - inheritance

### Topics for this week:
- Day 1 — Objects Deep Dive
    - Topics
        - What is an object
        - Key-value pairs
        - Accessing & updating values
        - Deleting properties
        - Nested objects
        - Looping objects (for...in)
        - Object.keys(), Object.values(), Object.entries()
    - Tasks
        - Create a user object with nested data
        - Add & remove keys
        - Loop through the object
        - Write a function to return all keys
        - Write a function to merge two objects

## Day-01
### What is an Object?
- The Object represents one of the Data Type in JS. It is used to store various keyed collection and more complex entitites, we store the data in key-value pair. We can create an Object by using the basic method Object(). 

### What is Key-value pairs?
- Key-value pairs are the fundamental and building blocks used to store and represent data, where key act as a unique identifier and is associated with a specific value.

### Accessing and Updating Values in Object
- We can use various methods to access and update the value of an object, for instance we can use dot (.) or bracket ([]) notations to access the value of an Object. To update the value in an Object we can assign the new value for instance, using dot notation we can do => obj.key1 = newValue, and for bracket notation we can do => obj[key] = newValue

### Deleting Properties
- We can use the "delete" to delete the property in an object, but it will acutally modify the original object which is not a good practice, another way to delete is by uusing destructing method which is, using "..." spread operator. for instance, const {age, ...otherPropertiesWillBeCopiedHere} = person.

### Nested Objects
- A value itself can be an Object, which gives us a nested object. And we can use dot or bracket notations to access and update.

### Looping Objects
- We can use for in loops to loop through and object, The for..in loop loops over keys of an Object. We should use this only for plain objects, not array we should use for..of loop for that.

### Object.keys(), Object.values(), Object.entries()
- These methods convert the object into Arrays.
- const user = {name: "junaid", age: 25, city: "Delhi"}
    - Object.keys(user) => ['name','age','city'] Array of Keys
    - Object.values(user) => ['junaid','25','Delhi'] Array of values
    - Object.entries(user) => [["name","junaid"], ["age","25"], ["city","Delhi"]] Array of [key,value] pairs
