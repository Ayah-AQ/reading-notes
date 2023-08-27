> Q1: **What is the motivation for adding a reducer?**
   >> Reducers help manage complex state logic and updates in a predictable way.

> Q2: **What are actions in the context of a reducer? How are they different than setting state directly?**
   >> Actions are objects describing what happened, while setting state directly modifies state. Actions are used in reducers to make controlled updates.

> Q3: **What common list operation is `useReduce` named for, and why?**
   >> `useReducer` is named after the "reduce" operation, which aggregates a list's values into a single value. It's used to manage state transitions in a more structured manner.

Q4: **When should you switch from `useState` to `useReducer`?**
   >> Switch to `useReducer` when state logic becomes complex or involves multiple sub-states, actions need to be handled in a structured way, or when performance optimizations are needed.