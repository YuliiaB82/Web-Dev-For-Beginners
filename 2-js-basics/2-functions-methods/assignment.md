# Fun with Functions

## Instructions

Create different functions, both functions that return something and functions that don't return anything.

See if you can create a function that has a mix of parameters and parameters with default values.

https://codepen.io/Blahovistna/pen/xxjNVEj?editors=0011

```javascript
function coffee(name) {
  const message = `It is your coffee, ${name}`;
  console.log(message);
}
coffee("Korey");

function pizza(name) {
  const message = `It is your banan pizza, ${name}`;
  return message;
}
console.log(pizza("Korey"));

function order(name, drink, food) {
  console.log(`Hi, ${name}, it is your ${drink} and ${food}!`);
}
order("Korey", "coffee", "pizza");

function addNumbers() {
  let firstNumber = 2;
  let secondNumber = 7;
  let addResult = firstNumber + secondNumber;
  console.log(addResult);
}
addNumbers();
```

## Rubric

| Criteria | Exemplary                                                                              | Adequate                                                         | Needs Improvement |
| -------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------- |
|          | Solution is offered with two or more well-performing functions with diverse parameters | Working solution is offered with one function and few parameters | Solution has bugs |
