// 1. As said before
JavaScript has a number type
this.say(3);
and a string type
this.say("Joshua");

// 2. Some basic arithmetic works as you'd expect with number type.
1 + 1; // = 2
0.1 + 0.3; // = 0.4
8 - 1; // = 7
10 * 2; // = 20
35 / 5; // = 7
(1 + 3) * 2; // = 8


// 3. There's also a boolean type.
true;
false;

// 4. Equality is ===
1 === 1; // = true
2 === 1; // = false

"Brak" === "Brak" // = true
var enemy = "Kratt"
enemy === "Kratt" // = true
enemy === "Brak" // = false

// More comparisons
1 < 10; // = true
1 > 10; // = false
2 <= 2; // = true
2 >= 2; // = true

// 5. As does `while`.
while (true){
    this.moveRight();
    this.moveUp();
    this.moveLeft();
}


// The `if` structure works as you'd expect.
var count = 0;
while(count < 10) {
  count = count + 1;
  console.log(count);
}
