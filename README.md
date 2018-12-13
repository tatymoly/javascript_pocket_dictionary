# javascript_pocket_dictionary
This repo contains a list of concepts explained as I personally understand them. I might be wrong so don't judge me, instead teach me. 💛

## Javascript

### 1. Javascript

Javascript is a lightweight scripting language, primarily used on the web. It allows you to implement complex things on web applications. It's also used to add interactive features to web apps. It was created by Netscape. 

Javascript is a multi paradigm programming language. It has functional programming, scripting, object oriented, imperative.

### 2. ECMA and ES6

Javascript is standardized by ECMA (European Computer Manufactures Association). They provide new features in each release.

In ES6, They introduced class-based objects, giving javascript a more object oriented paradigm (but it is still prototype oriented.) They also introduced arrow functions, let, const, and modules.

### 3. Arrow Functions

They are functions written in a simpler way. They are useful because they get ripped off the this making the scope depend on the execution context.

### 4. Let and Const

let and const will create a close scope for a variable, not like var which creates it globally. They prevent hoisting. They are new declarations that allow us to have a better management of the scope.

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

Is the most most fundamental async pattern in javascript. These are functions that will be executed once some other instruction has been done.

### 10. Callback hell

It happens when many callbacks are nested into one function.

### 11. Promises

Are an easier way to handle callbacks. They provide a more organized way to write our functions. Are basically the same, the next instruction wont be executed until the promise has a response.

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

Is a superset of javascript. It was developed by Microsoft. It is transpiled to javascript. Typescript makes code easier to read and understand. It is typed, which means you can assign a type of any variable, and that helps with immutability, because you wont change the type fo the value. Typescript can tell you when you have errors in your code. It has: string, number, undefined, null, symbol, boolean, turple, void and any.

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

They are the kind of function that will always return the same values for the same arguments.

## Angular

### 1. Modules

Declare a compilation context for a set of components. A module can associate related code such as services to form functions units. Just like javascript modules, NgModules can export functionality and also import it from other modules.

### 2. Components

They are logic exported as a class that handles functionality and data for your templates.

### 3. Decorators

Are functions that modify javascript classes. They have specific metadata, so the system knows what those classes mean and how they should work.

### 4. Directives

They provide logic and connect that data to your template.

### 5. Event Binding

They respond to users input by updating your application data.

### 6. Property Binding

They interpolate values from your app to the HTML.

### 7. Two-way data Binding

It means that changes in the DOM such as user choices are also reflected in your program data.

### 8. Services

They handle data and logic that will be shared all around your app. They are injectable.

### 9. Dependency Injection

It let you keep your components lean and efficient.

### 10. Routing

The routing is basically in charge of giving access to other components to the users. They can provide lazy-loading and we can manage Guards to make sure the user can navigate to that specific page.

### 11. Lazy Loading

Is basically loading our components on demand (only when we need them).

### 12. Rxjs

Is a library for reacting programming using observables to make it easier to compose asynchronous code. It provides better performance, better modularity and better debugging.

### 13. NgRx

Is an stage management library. When the app grows in size and complexity the stage management becomes harder.
