# Multiple Reducers Example

> **Q1: Why create multiple reducers?**
>> Multiple reducers are used to keep code organized, scalable, reusable, and easy to test in Redux.

> **Q2: How would you combine multiple reducers?**
>> You combine multiple reducers in Redux using the `combineReducers` function, creating a single root reducer.

> **Q3: How will you manage state as an immutable object? Why?**
>> Managing state as an immutable object in Redux is crucial for predictability, performance, features like undo/redo, and easier testing. It's done by always creating new state objects instead of modifying existing ones.

# Redux Docs: Using Combined Reducers

> **Q1: What is combineReducers used for?**
>> combineReducers is used to simplify the process of writing Redux reducers, which manage different parts of the application state.

> **Q2: How does combineReducers create the new state?**
>> combineReducers creates the new state by letting each slice reducer respond to and update its part of the state when an action is dispatched. It combines these updated slices into the new state.

> **Q3: How can you define initial state when using combineReducers?**
>> You can define initial state by providing a `preloadedState` when creating the store using `createStore`. Alternatively, the root reducer can return the initial state when the `state` argument is `undefined`, and you define the initial state within the slice reducers.

# Redux Docs: Combined Reducer Syntax

> **Q1: Why split reducing functions in a complex app?**
>> You split reducing functions in a complex app to manage different parts of the state independently, making your code more organized and easier to maintain.

> **Q2: What does `combineReducers` do?**
>> `combineReducers` is a function that combines different reducing functions into a single function, which you can use with `createStore` to manage the state of your Redux app.

> **Q3: What's a common convention for naming reducers?**
>> A common convention is to name reducers after the specific parts of the state they manage. You can use shorthand notation in ES6, like `combineReducers({ counter, todos })`, which is the same as `combineReducers({ counter: counter, todos: todos })`.