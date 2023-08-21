# **Thinking in React**

> Q1:Summarize the five steps of thinking in react.
>>1. **Break UI into Blocks:** Split the design into smaller pieces.
>>2. **Make Static Version:** Create a fixed, non-interactive draft.
>>3. **Find Changing Bits:** Identify what data will change.
>>4. **Connect Data Flow:** Set up how changes affect the view.
>>5. **Organize Data Locations:** Decide where data should be handled.

# **State: A Component’s Memory**

> Q1: What is one reason a local variable isn’t sufficient for managing a React component?
>> Local variables don't automatically update the screen when they change.

> Q2: What is the argument to the useState hook, and what are the two parts of its return array?
>> You give `useState` an initial value. It gives you the current value and a function to change it.

> Q3: How can Component A access state from Component B?
>> To share data between two components, put the data in a common parent and pass it down as a prop.
