---
title: "Week 1"
date: "2024-12-12"
description: "Write-Up for week 1 alongside Password Generator Assignment"
tags: ["html", "css", "js", "basic"]
weight: 1
---
# Week 1 Report
* **Variables**: Dynamically typed, Assigned using `var`, `let` or `const`
* **Data Types**: Can be checked using the `typeof()` function.
	* String: series of characters
	* Number: numbers (with or without decimal points)
	* Bigint: Normal integers are 64-bit and 15 digits accurate... Larger integers are bigint
	* Boolean: True or False
	* Undefined: Value of a variable when it has been declared but not assigned
	* Null: A variable is assigned with this value to represent "no value"
	* Object: Can be built-in of user defined. Built-ins include
		* objects: Kind of like Key-Value pairs like Dictionaries/Lists in other languages
		* arrays: collection of values of same datatype
		* dates
		* maps
		* sets
		* intarrays
		* floatarrays
		* promises
		* etc
* **Functions**: 
	* Declaration: Declaring a function  
		```js
        function name() { /* body */ }
        ```
	* Expression: Declaring a function without name (unless used in a variable)  
		```js
        const name = function() { /* body */ }
        ```
		```js
        const name = new Function("params", "body")
        ```
	* Arrow Functions: Short hand declaration of functions  
		```js
        const myFunction = (params) => expression;
        ```
		```js
        const myFunction = (params) => { /*body*/ };
        ```
* **Loops**:
	* For:  
		```js
        for (let i = 0; i < length; i++) { /*body*/ }
        ```
	* While  
		```js
        while(condition) { /*body*/ }
        ```
	* ForEach  
		```js
        array.forEach(function());
        ```
* **Let**: Scopes the variable in the current `{}` block.  Hoisted but not initialized. does not create a property on the global object. Re-declaration not allowed. `var` is the exact opposite. https://stackoverflow.com/questions/762011/what-is-the-difference-between-let-and-var
* **Const**:The const keyword has all the properties that are the same as the let keyword, except the user cannot update it and have to assign it with a value at the time of declaration. 
* **How JavaScript works on the web?**: https://www.freecodecamp.org/news/how-javascript-works-behind-the-scenes/
* **Necessity of JavaScript**: A universal language for website and web development which is integrated by default in basically all browsers. Maybe not the best language by design but great and lightweight nonetheless 
* **DOM**: DOM (Document Object Model) is a programming interface that represents the structure of a web page in a way that programming languages like JavaScript can understand and manipulate. But from info I was able to collect, not a inherent part of JavaScript itself. This is basically a tree of html elements.

# Week 1 Assignment
#### Create a simple password generator using javascript The user just clicks on a button and it should generate random mixed passwords.

### Submission
Code: https://github.com/anir183/iic-fgp/tree/main/static/week1-passgen  
Website: [https://anir183.github.io/iic-fgp/week1-passgen](/iic-fgp/week1-passgen)  
  
![project-image](/iic-fgp/images/week1_project.png)
