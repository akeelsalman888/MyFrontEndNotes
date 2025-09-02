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

