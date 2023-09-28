1. **Core Components of React Native:**
   - **View**: A container for screen content, like a box to hold things.
   - **Text**: Displays words on the screen, similar to text in a book.
   - **Image**: Shows pictures on the screen, like a photo frame.

2. **Problem Solved by React Native ("Why Native?"):**
   React Native creates mobile apps that closely resemble native mobile apps in terms of look and feel. It's called "native" because it utilizes the same building blocks as actual mobile apps, allowing you to write code once and use it on different phones.

3. **Building Blocks of React Native vs. React (for the web):**
   - **React Native**: Uses real mobile components for the screen, JavaScript code for functionality, and styles for a unique look.
   - **React (for the web)**: Utilizes virtual sketches (plans) for UI, HTML, and styles for web pages, and web-specific elements.

4. **Expo's Solution:**
   Expo simplifies React Native app development by providing tools and services for tasks like setup, building, and deployment, making the process more accessible to beginners.

5. **Expo Workflow:**
   Expo is often referred to as the "Managed" workflow because it handles a significant portion of app development complexity.

6. **Difference Between React Native and Expo:**
   React Native is the core framework for mobile app development, offering flexibility but with more complexity management. Expo builds on React Native, providing a simplified, user-friendly environment with less setup and more convenience.

7. **Expo Snack:**
   Expo Snack is a development tool that lets you write, test, and share React Native code interactively.

8. **Ejecting in Expo:**
   In the context of Expo, "eject" means leaving Expo's simplified environment to gain greater control over native Android and iOS projects.

9. **When Not to Eject:**
   Avoid ejecting if you prefer Expo's simplicity and don't need extensive customization of native code.

10. **When to Choose Ejecting:**
    Ejecting is chosen when you require full control over native projects, specific native code integrations, or when using Expo APIs in a standard native project. It offers flexibility but requires managing build configurations and native code. Note that ExpoKit ejection is deprecated after SDK 38.