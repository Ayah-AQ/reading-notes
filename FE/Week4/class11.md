> What is the first principle of Redux?
>> The first principle of Redux is "Single Source of Truth," meaning that all of your application's state is stored in one central place called the "store."

> What is a store, and what do reducers do within that store?
>> A **store** in Redux is like a container that holds all the data for your application. **Reducers** are functions used in the store to determine how the data should change when actions occur. They update the data in a safe and predictable way.

> Name three methods provided by `createStore` in Redux, and explain their uses.
>> 1. **`getState()`**: It's used to get the current state of your application.
>> 2. **`dispatch(action)`**: This is for sending actions that describe what should happen in your app.
>> 3. **`subscribe(listener)`**: It helps you listen for changes in the state so you can react accordingly.

> Explain `combineReducers()` to a non-technical recruiter and why it's useful.
>> `combineReducers()` is like the organizer for your application's data. It takes all the different pieces of data and makes sure they work together without getting mixed up. This is really handy as your application gets bigger and more complex because it keeps things neat and manageable.