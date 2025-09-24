# MyFrontEndNotes

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


E is accessible anywhere in its scope.

This is the subtle but important difference.
