# MyFrontEndNotes

************
REOURCES
***********
Week 1: HTML

What are semantic tags in HTML, and why are they important?
HTML Validation: Explore the importance of HTML validation and how it can help ensure well-formed and error-free web pages. Provide a small contextual example.
Explore the role of meta tags in HTML for SEO. Research common meta tags such as <title>, <meta name="description">, and <meta name="keywords">. Investigate their impact on search engine rankings and best practices for optimizing them.
What is the difference between a block-level element and an inline element?
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Week 2: CSS_github

https://git-scm.com/docs
https://git-scm.com/docs/git#_git_commands
chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://training.github.com/downloads/github-git-cheat-sheet.pdf
https://docs.github.com/en/get-started/learning-about-github/github-glossary
https://docs.github.com/en/get-started/start-your-journey
What are CSS grid and flexbox? When might you use one over the other?
Explore the use of CSS custom properties (variables) and their benefits in managing reusable styles and theming. Research how CSS variables can improve code maintainability and enable dynamic styling changes.
Investigate the role of CSS in ensuring sufficient contrast and color accessibility for users with visual impairments. Research techniques for implementing accessible color schemes.
Investigate the usage and benefits of CSS selectors. Research the different types of selectors, such as element selectors, class selectors, ID selectors, and pseudo-classes. Explore how selectors allow you to target specific elements or groups of elements for styling. Provide examples of common use cases for each type of selector and best practices for writing efficient and maintainable CSS selectors.
Explore the CSS box model and its significance in determining the layout and spacing of elements on a webpage. Research the components of the box model, including content, padding, border, and margin.
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 3: Bootstrap

https://getbootstrap.com/docs/5.0/migration/

Name five different Bootstrap components and describe how they work.
How does the Bootstrap grid system work?
What are the available options for incorporating Bootstrap into a project (CDN, npm, etc.)? Why might you use an npm install over a CDN?
How does Bootstrap support accessibility, and what are the best practices for ensuring an accessible Bootstrap project?
What are some alternatives to Bootstrap? Provide a short summary of one that interests you.

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 4: JS1 - JavaScript Introduction

https://developer.mozilla.org/en-US/docs/Web/JavaScript
https://docs.oracle.com/javase/tutorial/
https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Adding_interactivity
https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content
https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Styling_the_content
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 5: JS2 - Loops and Conditions
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 6: JS3 - Arrays & Functions

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects#objects_and_properties
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Equality_comparisons_and_sameness
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects#comparing_objects
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 7: JS4 - ECMAScript 6 & Intermediate
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
https://262.ecma-international.org/6.0/
https://262.ecma-international.org/
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions#the_arrow_function_expression
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises#chaining
What are the differences between var, let, and const?
What are the differences between callbacks and promises?
What are some new features introduced in ES6?
How does a promise work?
What are the common use cases for higher-order functions in JavaScript, and how do they enhance code modularity and reusability?
What are pure functions? How do they contribute to code predictability, testability, and ease of debugging? 
How can objects be used to store and organize data in JavaScript, and what are the advantages of using objects over other data structures like arrays or maps?

Coding Steps:
All questions should be printed to your Browser's console using console.log()
Create an array called ages that contains the following values: 3, 9, 23, 64, 2, 8, 28, 93.
Programmatically subtract the value of the first element in the array from the value in the last element of the array.
Do not use numbers to reference the last element, find it programmatically.
ages[7] - ages[0] is not allowed!
Add a new age to your array and repeat the step above to ensure it is dynamic. (works for arrays of different lengths).
Use a loop to iterate through the array and calculate the average age.
Create an array called names that contains the following values: 'Sam', 'Tommy', 'Tim', 'Sally', 'Buck', 'Bob'.
Use a loop to iterate through the array and calculate the average number of letters per name.
Use a loop to iterate through the array again and concatenate all the names together, separated by spaces.
How do you access the last element of any array?
How do you access the first element of any array?
Create a new array called nameLengths. Write a loop to iterate over the previously created names array and add the length of each name to the nameLengths array.
For example:
let names = ["Kelly", "Sam", "Kate"];    // starting with this array
let nameLengths = [5, 3, 4];             // create a new array
Write a loop to iterate over the nameLengths array and calculate the sum of all the elements in the array.
Write a function that takes two parameters, word and n, as arguments and returns the word concatenated to itself n number of times. (i.e. if I pass in 'Hello' and 3, I would expect the function to return 'HelloHelloHello').
Write a function that takes two parameters, firstName and lastName, and returns a full name. The full name should be the first and the last name separated by a space.
Write a function that takes an array of numbers and returns true if the sum of all the numbers in the array is greater than 100.
Write a function that takes an array of numbers and returns the average of all the elements in the array.
Write a function that takes two arrays of numbers and returns true if the average of the elements in the first array is greater than the average of the elements in the second array.
Write a function called willBuyDrink that takes a boolean isHotOutside, and a number moneyInPocket, and returns true if it is hot outside and if moneyInPocket is greater than 10.50.
Create a function of your own that solves a problem. In comments, write what the function does and why you created it.
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 8: JS5 - Object Oriented Programming
https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Advanced_JavaScript_objects/Object-oriented_programming
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_classes#overview_of_classes
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_classes#why_classes
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling#exception_handling_statements

What are the four pillars of Object-Oriented Programming? Explain each pillar.
What is the relationship between a Class and an Object?
What is an exception, and what are the best practices for handling them?
How does the 'extends' keyword work with JavaScript classes?
Research the role of the 'this' keyword in JavaScript classes and how it refers to the current object instance within methods.
What is "encapsulation" in JavaScript?
What are the differences between instance methods and static methods in JavaScript classes?
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 9: JS6 - DevTools, Debugging, & Unit Tests
https://developer.chrome.com/docs/devtools/overview/
https://developer.chrome.com/docs/devtools/open/
https://developer.chrome.com/docs/devtools/shortcuts/
https://news.yale.edu/2017/02/10/grace-murray-hopper-1906-1992-legacy-innovation-and-service
https://code.visualstudio.com/docs/debugtest/debugging
https://jestjs.io/docs/getting-started               //NEW TESTING TOOL
https://mochajs.org/next/
https://mochajs.org/#getting-started                // OLD ONE
https://www.chaijs.com/
https://www.chaijs.com/guide/
https://www.w3schools.com/js/js_debugging.asp
https://agilealliance.org/glossary/tdd/
https://dev.to/pat_the99/basics-of-javascript-test-driven-development-tdd-with-jest-o3c















**Why is let used instead of VAR?
let allows you to declare variables that are limited to the scope of a block statement, or expression on which it is used, 
unlike the var keyword, which declares a variable globally, or locally to an entire function regardless of block scope.
************************************

**Read about Execution Context and Lexical Environmnet.

**There are two kinds of Execution Context in JavaScript:
1.Global Execution Context (GEC)
2.Function Execution Context (FEC)

++ Since every function call gets its own FEC, there can be more than one FEC in the run-time of a script ++ 

**Clouser ???

Encapsulation = “Hide the data inside a capsule and control access to it.”
Abstraction = “Hide the complex implementation and show only the necessary functionality.”
Method overriding: Both Dog and Cat override the speak method from Animal.
Polymorphism: The makeAnimalSpeak function treats Dog and Cat instances as objects of type Animal, demonstrating that the same method speak() behaves differently based on the object.
 polymorphism is advantageous because it enables programmers to create objects with identical functionality, i.e., functions with identical names that operate identically. In some other areas of the OOP framework, you can, however, change some portions of the shared code or even the entire


// while
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}

//do...while
let i = 0;
do {
    console.log(i);
    i++;
} while (i < 5);


//for
for (let i = 0; i < 5; i++) {
    console.log(i); // 0 1 2 3 4
}


//for...in
let person = {name: "Akeel", age: 20};
for (let key in person) {
    console.log(key); // name, age
    console.log(person[key]); // Akeel, 20
}


//for...of
let colors = ["red", "green", "blue"];
for (let color of colors) {
    console.log(color); // red, green, blue
}

//forEach
let numbers = [1, 2, 3];
numbers.forEach(function(num) {
    console.log(num); // 1 2 3
});

Important to note, the ! operator has a higher precedence than the && and || operators. This means that expressions with ! will be evaluated first before expressions with && and ||. It is important to keep operator precedence in mind when writing complex expressions, as it can affect the outcome of your code.

all values are truthy except false, 0, -0, 0n, "", null, undefined, and NaN

Iteration - each execution of the loop's code block or every time the loop runs.
Iterator - a variable used to keep track of the current iteration count, customarily i or j for nested loops. This can be any variable name

By using i++, the increment operator increments by one and returns the value before incrementing.  let i = 5;  console.log(i++); // prints 5 (then i becomes 6)

for of loop: Allows you to iterate over the values of an iterable object, such as an Array.

Using an Array Literal:

    var myArray = [];  // Output: [] , an empty Array literal

    var myOtherArray = [1, 2, 3];  // Output: [1,2,3]

    var myStringArray = ["apple", "banana", "orange"];  // Output: ["apple","banana","orange"]
Using an Array Constructor:

    let numsArray = new Array(3);  // Output: [ , , ]  an empty Array with 3 slots

    let myOtherNumsArr = new Array(1, 2, 3);  // Output: [1, 2, 3]

    let fruitsArr = Array ("apple", "banana", "orange");  // Output: ["apple","banana","orange"]

     let numbers = [1, 2, 3, 4, 5];
    numbers.length = 3;
    console.log(numbers); // Output: [1, 2, 3]

      let numbers = [1, 2, 3];
    numbers.length = 5;
    console.log(numbers);  // Output: [1, 2, 3, undefined, undefined]
    
//array.splice(startIndex, numOfElementToBeRemoved, item1, item2, ...);

Array.prototype.unshift() has similar behavior to push(), but applied to the start of an array.

| Method             | What it does                              | Mutates original array? | Return value     | Example                                               |
| ------------------ | ----------------------------------------- | ----------------------- | ---------------- | ----------------------------------------------------- |
| **`push()`**       | Adds elements to the **end** of an array  | ✅ Yes                   | New array length | `let arr=[1,2]; arr.push(3); // arr=[1,2,3]`          |
| **Spread (`...`)** | Expands array elements into another array | ❌ No                    | A new array      | `let arr=[1,2]; let newArr=[...arr,3]; // [1,2,3]`    |
| **`concat()`**     | Merges arrays or values into a new array  | ❌ No                    | A new array      | `let arr=[1,2]; let newArr=arr.concat(3); // [1,2,3]` |

push() = change same array.

spread = copy/expand into new array.

concat() = merge into new array.


An Object is a variable that can hold many variables.

Objects are collections of key-value pairs, where each key (known as property names) has a value.

Objects can describe anything like houses, cars, people, animals, or any other subjects.

Different cars have the same properties, but the property values can differ from car to car.

Different cars have the same methods, but the methods can be performed at different times.


//CLass Declaration VS CLass Expression
// Class Declaration
console.log(A); // ❌ ReferenceError
class A {}

// Class Expression
const B = class {};
console.log(B); // ✅ [class B]
Explanation:

A (declaration) cannot be used before it’s declared → ReferenceError.

B (expression) behaves like a regular variable → only exists after assignment.

You also can do anonymous expressions:

js
Copy code
const C = class {};
console.log(C.name); // "" (empty)




// named class expression example:

const D = class MyClass {
  sayHi() { console.log("Hi"); }
};

console.log(D.name); // "MyClass"

const obj = new D();
obj.sayHi(); // "Hi"

// But MyClass is NOT accessible outside
console.log(typeof MyClass); // ❌ ReferenceError


Key points:

The name (MyClass) exists only inside the class body.

Outside, you must use the variable (D) to refer to the class.

So compared to a declaration:

class E {}
console.log(E.name); // "E"


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Week 10: JavaScript & DOM Manipulation
https://developer.mozilla.org/en-US/docs/Web/API
https://www.guvi.in/blog/guide-for-html-dom/
https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector
http://developer.mozilla.org/en-US/docs/Web/API/Node
https://www.w3schools.com/jsref/prop_node_textcontent.asp
https://www.w3schools.com/jsref/prop_html_style.asp
https://www.w3schools.com/jsref/prop_element_classlist.asp
https://www.w3schools.com/jsref/met_domtokenlist_toggle.asp
https://www.w3schools.com/jsref/met_domtokenlist_add.asp
https://www.w3schools.com/jsref/dom_obj_style.asp
https://www.w3schools.com/jsref/met_document_createelement.asp
https://www.youtube.com/watch?v=l-0nPnSvbX8
https://www.youtube.com/watch?v=on9p11gv1k4&t=163s
https://www.youtube.com/watch?v=8LWQNnVAMh4
https://www.youtube.com/watch?v=RQ40ZilvCOg
https://www.youtube.com/watch?v=XF1_MlZ5l6M
DOM Research Details
List and explain the JavaScript methods that enable us to select elements from the DOM.
What is the document object? What are some other methods available on the document object that don't select elements from the DOM? Why is the virtual DOM faster?
What are the differences between the innerHTML and textContent properties in the DOM?
What is the purpose of the createElement, appendChild, and removeChild methods in the DOM?
Investigate the concept of event listeners in JavaScript and how they can be used to respond to user interactions. Research how to attach event listeners to HTML elements and handle events such as clicks, mouse movements, or keyboard input. 



E is accessible anywhere in its scope.

This is the subtle but important difference.

debugger:  a computer program that helps find and correct errors in other computer programs.
breakpoint:  a signal that informs the debugger to temporarily suspend execution of the program at a certain point in the code.
