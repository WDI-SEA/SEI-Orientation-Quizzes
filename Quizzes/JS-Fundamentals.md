# JavaScript Fundamentals

## Your Name: ______________________ Your Score: ___________________

#### 1) In JavaScript, how can I declare a variable? (Circle ALL correct answers - there may be more than one! 8 points)

* `x = 5`
* `let x = 5`
* `5 = x`
* `const x = 5`
* `var 5 = x();`
* `var(...args);`
* `var x = 5;`
* `var = x;`

#### 2) What does `===` do that `==` doesn't? (1 point)

* a) Checks for equality (instead of assignment)
* b) Checks for a deep copy of an array
* c) Checks that the types being compared match (as well as value)
* d) Assigns a boolean value type when appropriately matched to the incoming data
* e) None of the above

#### 3) What does `==` do that `=` doesn't? (1 point)

* a) Checks for equality (instead of assignment)
* b) Checks for a deep copy of an array
* c) Checks that the types being compared match (as well as value)
* d) Assigns a boolean value type when appropriately matched to the incoming data
* e) None of the above

#### 4) An `else` can live independently from an `if` statement. True or False? (1 point)

* a) True
* b) False
* c) All of the Above 

**Consider the following code, then answer questions 5 and 6**

```js
let numPeople = 2;
if (numPeople == 1) {
  console.log('Hello future student!');
}
else if (numPeople == 2) {
  console.log('Hello to both of you future students!');
}
else if (numPeople > 0) {
  console.log('Hello SEI class!');
}
```

#### 5) An `if` statement includes a conditional piece. In the code above, this condition is `numPeople == 1`. This conditional: (1 point)

* a) Evaluates to a boolean
* b) Evaluates to an integer
* c) Evaluates to an array
* d) Doesn't evaluate because we need `===` instead of `==`
* e) Doesn't evaluate because we need `=` instead of `==`
