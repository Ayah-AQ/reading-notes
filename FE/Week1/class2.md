# **Thinking in React**

> **What are the key steps for thinking in React?**
>> Here they are, simplified:
>>1. **Break UI into Blocks:** Split the design into smaller pieces.
>>2. **Make Static Version:** Create a fixed, non-interactive draft.
>>3. **Find Changing Bits:** Identify what data will change.
>>4. **Connect Data Flow:** Set up how changes affect the view.
>>5. **Organize Data Locations:** Decide where data should be handled.

# **State - A Component’s Memory**

> **Why don't local variables work well in React components?**
>> Local variables don't automatically update the screen when they change.

> What's the deal with `useState` in React?**
>> You give `useState` an initial value. It gives you the current value and a function to change it.

> How can one component access another component's state?**
>> To share data between two components, put the data in a common parent and pass it down as a prop.