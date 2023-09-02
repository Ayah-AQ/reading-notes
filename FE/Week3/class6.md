# Context API

## Choosing the State Structure

> Q1: What are the five principles for structuring state in React?
>> The five principles for structuring state in React are:
>> 1. **Single Source of Truth**: Keep one central state for your app.
>> 2. **State Is Read-Only**: Treat state as unchangeable; create new states when needed.
>> 3. **Changes Are Made with Pure Functions**: Update state using pure functions (reducers).
>> 4. **Data Flow is Unidirectional**: Ensure data flows from parent to child components.
>> 5. **State Should Be Normalized**: Simplify complex state structures when handling data.

## Passing State Deeply with Context

> Q1: Why are Contexts used in React?
>> Contexts in React are used to avoid prop drilling, where data is passed down through many components. They enable sharing data across the component tree without explicit prop passing.

> Q2: What's a technique to use before `useContext`?
>> Before using `useContext`, consider using the default prop system to pass data between components. However, this can become unwieldy in complex hierarchies.

> Q3: What complements `useContext` in complex apps?
>> For complex React apps, consider using `useReducer` in conjunction with `useContext`. This combination helps manage state and actions in a more organized way, particularly in large applications.