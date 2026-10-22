
## Question - 1
---
Frontend JavaScript:
Runs in the web browser of the system and is used to create interactive and dynamic web pages.
It can also manipulate HTML and CSS using the DOM

Backend JavaScript:
Runs on the server using Node.js and is used to handle business logic, databases, authentication, and APIs.

---
## Question - 2
---
DOM stands for Document Object Model. It is a programming interface that represents an HTML document as a tree of objects. JavaScript uses the DOM to access and modify HTML elements, attributes, styles, and content.

----

## Question - 3
---
An event is an action or occurrence that happens in a web browser and can be detected by JavaScript. Events can be triggered by users or by the browser itself.

Common examples of events include:

- `click` – when an element is clicked.
    
- `mouseover` – when the mouse moves over an element.
    
- `keydown` – when a keyboard key is pressed.
    
- `submit` – when a form is submitted.
    
- `load` – when a page or resource finishes loading.

---
## Question - 4
---
The event loop is a mechanism that allows JavaScript to handle asynchronous operations even though JavaScript typically executes code on a single main thread.

It checks whether the call stack is empty and coordinates the execution of queued callbacks and other scheduled tasks.

The main concepts are:

1. Call Stack: Executes synchronous JavaScript code.
    
2. Web APIs or runtime APIs: Handle operations such as timers and browser events.
    
3. Task Queue: Holds callbacks for tasks such as `setTimeout`.
    
4. Microtask Queue: Holds tasks such as Promise callbacks, which are generally processed before the next task.
    
5. Event Loop: Coordinates when queued work can execute.

---
## Question - 5
---
Hoisting is JavaScript's behavior of processing declarations before executing the code in their scope. However, different types of declarations behave differently.

- `var` declarations are hoisted and initialized with `undefined`.
    
- `let` and `const` declarations are hoisted but cannot be accessed before initialization.
    
- Function declarations can generally be called before their definition appears in the code.

---

## Question - 6
---
Event bubbling is a process in which an event triggered on an element propagates upward through its parent elements in the DOM tree.

For example, if a button is inside a `div`, clicking the button can trigger click handlers on the button, the `div`, and other ancestors.

---

## Question - 7
---
These are three common ways to define functions in JavaScript.

### A. Named function

A named function is a function that has a name. It can be called using that name and can generally be called before its declaration.


### B. Anonymous function

An anonymous function is a function expression without its own function name. It is often assigned to a variable or passed as a callback.


### C. Arrow function

An arrow function uses the `=>` syntax. It provides a shorter way to write functions and does not have its own `this` value.

---

## Question - 8
---
### `for...of` loop

The `for...of` loop iterates over the values of an iterable, such as an array or string.

```
const fruits = ["Apple", "Banana", "Mango"];

for (const fruit of fruits) {
  console.log(fruit);
}
```

### `for...in` loop

The `for...in` loop iterates over the enumerable property keys of an object. When used with an array, it gives the array's index keys rather than its values.

```
const student = {
  name: "Rahul",
  age: 20,
  course: "JavaScript"
};

for (const key in student) {
  console.log(key, student[key]);
}
```

----

## Question - 9
---

JavaScript provides many built-in array methods to add, remove, search, and transform elements.

### 1. `push()`

Adds one or more elements to the end of an array and returns the new length.

### 2. `pop()`

Removes the last element from an array and returns the removed element.

### 3. `map()`

Creates a new array by applying a function to every element of the original array.

### 4. `filter()`

Creates a new array containing only the elements that satisfy a given condition.

### 5. `forEach()`

Executes a provided function once for each element of an array. It returns `undefined`.

---

## Question - 10
---

A callback function is a function passed as an argument to another function so that it can be called by that function, either immediately or later.

Callbacks are commonly used for event handling, asynchronous operations, and array methods.