# 1. What is the difference between var, let, and const?

var: Function-scoped variable that can be redeclared and reassigned. It is hoisted with undefined.

let: Block-scoped variable that can be reassigned but cannot be redeclared. It is hoisted but stays in the Temporal Dead Zone.

const: Block-scoped variable that cannot be redeclared or reassigned after declaration. It is also hoisted but stays in the Temporal Dead Zone.
# 2. What is the difference between map(), forEach(), and filter()?

map().: This method transform every element of a array and return a new array by not modifying original array.

forEach() this method happened loop of any array and return nothing

filter() this method return a new array based on condition we set and the new element of new array is thosw whose true.
# 3. What are arrow functions in ES6?

Arrow functions are a shorter syntax for writing functions. They are usually anonymous and do not have their own this.
# 4. How does destructuring assignment work in ES6?

Destructuring means extract value from arrays or objects To destructuring from array we use an array and put relevant name for pick value. To Destructuring form object we used an object left side and use property name in this object thats pick the value.
# 5. Explain template literals in ES6. How are they different from string concatenation?

Template literals is write with backticks `` inside of this its a kind of string that allow embedding variable and expressing by using ${} syntax. But string written by "" of '' don't allow it.
