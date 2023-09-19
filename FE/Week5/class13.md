# Async Actions

> Why use Redux middleware?
>> Redux middleware is used to handle special tasks, like managing asynchronous actions (e.g., API calls), in a Redux app, making it cleaner and more organized.

> Describe the Redux Async Data Flow.
>> In Redux's async flow, you use middleware like Redux Thunk to manage asynchronous tasks. Thunk middleware lets you dispatch actions at different stages of an async operation (start, success, error).

> How do we handle async in Redux?
>> To handle async tasks in Redux, we use middleware like Redux Thunk. We create action creators that return functions (thunks) to manage async logic and dispatch actions during the async process.

# Thunk Middleware

> Why use redux-thunk middleware?
>> Redux Thunk middleware is used for handling async actions in Redux. It lets you create action creators that return functions instead of simple actions.

> What does Redux Thunk allow action creators to return?
>> Redux Thunk allows action creators to return functions.

> How is the return value from the inner thunk function accessed?
>> The inner thunk function can access `dispatch` to send actions and `getState` to access the current state of the Redux store. These are provided by Redux Thunk.