# OOP: Use a Constructor to Create Objects
Use the Dog constructor from the last lesson to create a new instance of Dog, assigning it to a variable hound.
# Solution:
```javascript
function Dog() {
  this.name = "Rupert";
  this.color = "brown";
  this.numLegs = 4;
}
// Only change code below this line
let hound = new Dog();
```