### Goal: Write your own “documentation” for the higher order functions
**Your documentation should include:**
- A description of the purpose
- A description of the syntax
- An example
- An explanation of the example
- Any additional notes/details

---
Your documentation here: 
## Higher Order Functions

**Definition**: An higher order function is a function that takes in another as an argument or returns a function as a result. Higher-order functions allow us to be more flexible with how we with how we interact with our arguments. For example Array.prototype.map, array.prototype.filter and arr.prototype.reduce, are some of the higher order functions.

**Purpose**: Higher order functions allow us to abstract over action, not just values

```js
const doubleFunc = function(x) {
return x * 2;
}
const doubleUp = doubleUpFunc;
console.log('Double', doubleUp(50))
// This code will log the string `Double 100` to the console
```
**Explanation**: 
