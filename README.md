# arrow_functions_theory
Arrow function expressions

Arrow functions offer a more concise syntax for writing function expressions and have some distinct behaviors, particularly around the use of this.
The arrow function syntax looks like this:
  (param1, param2) => {
    // function body
  }
Simple expressions that omit the curly braces and the return keyword:
  (param1, param2) => param1 + param2;
Arrow functions are more compact than regular function expressions:
This: 
  function sum(a, b) {
  return a + b;
}
Become this: 
  const sum = (a, b) => a + b;
Arrow functions are most useful in places where you need a function expression, 
such as in callbacks (e.g., event handlers, timers, promises):
  const numbers = [1, 2, 3, 4];
  const doubled = numbers.map(num => num * 2); // [2, 4, 6, 8]
