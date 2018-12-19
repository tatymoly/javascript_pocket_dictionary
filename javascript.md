
### 1. Javascript

Javascript is a lightweight scripting language, primarily used on the web. It allows you to implement complex things on web applications and is also used to add interactive features to web apps. It was created by Netscape. 

Javascript is a multi paradigm programming language. It has functional, scripting, "object oriented", imperative. (More?)

### 2. ECMA and ES6

Javascript is standardized by ECMA (European Computer Manufactures Association). They provide new features in each release.

In ES6, They introduced class-based objects, giving javascript a more object oriented paradigm (but it is still prototype oriented.) They also introduced arrow functions, let, const, and modules.

### 3. Arrow Functions

They are functions written in a simpler way. They are useful because they get ripped off the **this** making the scope depend on the execution context.

### 4. Let and Const

They are new declarations that allow us to have a better management of the scope.
let and const will create a close scope for a variable, not like var which creates it globally. They prevent hoisting. 

### 5. Hoisting

Hoisting occurs when you don't have your variables scope well defined. Javascript takes the last value and push it to the top of the document. It can cause variable re assignment.

### 6. JS Engine

Javascript works thanks to the js engine. For each browser we have an engine. Chrome has V8, Firefox Gecko and Spider Monkey, Safari has Nitro and Edge Chakra.

V8 translates javascript code into more efficient machine code, at execution, by implementing just in time compiler. It doesn't produce bytecode or any intermediate code.

The V8 engine is composed by the memory heap and the call stack. The memory heap is where our memory is allocated. The call stack is a data structure which records basically where in the program we are. Each entry in the call stack is called stack frame.

### 7. Blowing the stack

This happens when you reach the maximum call stack size, it can happen quite easily especially if you are using recursion.

### 8. Asynchronous Callbacks

To avoid blocking the UI and making the browser unresponsive we can use asynchronous callbacks.

### 9. Callbacks

It's the most fundamental async pattern in javascript. These are functions that will be executed once some other instruction has been done.

### 10. Callback hell

It happens when many callbacks are nested into one function.

### 11. Promises

An easier way to handle callbacks. They provide a more organized way to write our functions. They are basically the same as **Callbacks**: the next instruction wont be executed until the promise has a response.

### 12. Closures

It's a feature in javascript when an inner function has access to the outer function's variables. It is useful because of the scope chain.

- it has access to its own scope
- it has access to the outer function variables
- it has access to global variables

### 13. Object Literals

They are a comma separated list of name-values pairs wrapped in curly braces. They encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables.

### 14. Prototype Inheritance

It is a reference to another object and it is used whenever JS can't find the property you're looking for on the current object.

Whenever you call a property on an object and it doesn't exist, javascript will go to the prototype object and look for it there.

### 15. Functional Mixins

Mixins are a form of object composition, where component features get mixed into a composition object so that properties for each mixin become properties of the composite object. They combine closure and dynamic objects.

Functional mixins are composable functions which mix new properties or behaviors with properties from a given object.

### 16. Typescript

It's a superset of javascript. It was developed by Microsoft. It is transpiled to javascript. Typescript makes code easier to read and to understand. It is typed, which means you can assign a type of any variable, and that helps with immutability, because you won't be able to change the type of the value. Typescript can tell you when you have errors in your code. It supports several types: string, number, undefined, null, symbol, boolean, turple, void and any.

### 17. Classes

A class is a blueprint from which we can create objects that share the same configuration properties and methods.

### 18. Interface

Is a group or related properties and methods that describe an object, but neither provide implementation nor initialization for them. The typescript compiler uses interfaces for type checking proposes.

### 19. Observables

They are just like promises but they can have multiple values over time and they can be cancelled (unsubscribe).

### 20. Primitives Javascript

string, number, undefined, symbol, boolean, the rest are objects (functions, arrays, prototypes)

### 21. Objects

An object is a collection of related data and/or functionality which are called properties and methods when they are inside objects.

### 22. Constructor

The constructor is an ordinary function that is used to produce a specialized type of object.

### 23. Iterators

An object is an iterator when it knows how to access to the element of a collection one by one. This object has a next method, which returns the next element in the sequence. It returns an object with two properties: done and value.

### 24. Generators

It is a special type of function that works as an iterator fabric. They are described as pausable functions.

### 25. Garbage Collector

Is an algorithm that automatically performs memory management. If not treated the right way it can provoke memory leaks.

### 26. Pure functions

They are the kind of function that will always return the same values for the same arguments, without observable side effects.
