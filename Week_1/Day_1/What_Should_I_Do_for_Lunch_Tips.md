# Information about this file below

This is a decision making file that uses console.log statements with conditional logic to tell you how to approach your free time for lunch purposes.

below is the code that made that all work:

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry === true && availableTime < 20) {
    console.log("pick up a snack or grab something you have ready at home.");
  } else if (hungry === true && availableTime >= 20 && availableTime <= 30) {
    console.log(
      "you deserve a break and should take time to cook a tasty meal."
    );
  } else if (hungry === true && availableTime > 30) {
    console.log(
      "this is an intense program after all and you should probably reconsider."
    );
  } else if (hungry === false) {
    console.log("Wait until your hungry");
  } else {
    console.log("I don't know what to do!");
  }
};
```
