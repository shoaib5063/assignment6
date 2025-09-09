**1. What is the difference between var, let, and const?**
var: Function-scoped, hoisted to the top of its scope, can be re-declared and updated. Often leads to bugs due to unexpected behavior.
let: Block-scoped, not hoisted in the same way, can be updated but not re-declared in the same scope. Safer for mutable values.
const: Block-scoped, must be initialized at declaration, cannot be re-assigned. However, objects/arrays declared with const can still have their contents modified.

**2.What is the difference between var, let, and const?**
var: Function-scoped, hoisted to the top of its scope, can be re-declared and updated. Often leads to bugs due to unexpected behavior.
let:Block-scoped, not hoisted in the same way, can be updated but not re-declared in the same scope. Safer for mutable values.
const: Block-scoped, must be initialized at declaration, cannot be re-assigned. However, objects/arrays declared with const can still have their contents modified.

**3.Arrow functions are a shorter syntax for writing functions:**
const add = (a, b) => a + b; They don’t have their own this binding; instead, they use the this value from their enclosing scope (lexical this).
They’re best used for small, concise functions, especially as callbacks.

**4. How does destructuring assignment work in ES6?**
Destructuring allows unpacking values from arrays or properties from objects into separate variables.Example with arrays:
const [first, second] = [10, 20];
console.log(first); 
Example with objects:
Copy code
const { name, age } = { name: "Asha", age: 25 };
console.log(name); 

**5. Explain template literals in ES6. How are they different from string concatenation?**
Template literals use backticks (`) and allow embedded expressions with ${}.Example:
const name = "Rahim";
console.log(`Hello, ${name}!`);
Differences:
Easier to read than string concatenation ("Hello, " + name + "!").
Support multi-line strings without special characters.
Allow interpolation of variables and expressions directly inside strings.
