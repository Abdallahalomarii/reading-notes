# React 2 Reading Notes

## React - Conditional Rendering

Conditional rendering in React allows you to show or hide components or elements based on certain conditions. It's a crucial concept for building dynamic user interfaces. Some key points to remember:

- You can use `if` statements, ternary operators, or logical operators like `&&` and `||` for conditional rendering.
- The `map` function is often used to iterate through arrays and conditionally render elements.
- Conditional rendering helps create responsive UIs that adapt to user interactions.

## React - Lists & Keys

Lists are a fundamental part of UI development. In React, rendering lists efficiently requires using keys to help React identify which items have changed, been added, or removed. Key points include:

- Keys should be unique among siblings but can be repeated across different lists.
- When rendering dynamic lists, React relies on keys to optimize updates and minimize DOM manipulation.
- Using the `map` function in combination with keys is a common practice when rendering lists.

## React - Forms

Working with forms in React involves handling user input and managing form state. Important concepts include:

- Controlled components: Form elements are controlled by React's state.
- Handling form submission and validation.
- Using controlled components with React hooks like `useState` or `useForm`.

## React - Lifting State

Lifting state in React refers to the practice of moving the state of a component up the component tree to a common ancestor. This is used for sharing state between sibling components. Key takeaways:

- Lifting state can make your component hierarchy more manageable and efficient.
- Props are used to pass data and functions down to child components.
- Changes in the lifted state will propagate down to all child components.

## React - Composition vs Inheritance

React promotes composition over inheritance. This means that instead of relying heavily on class inheritance, you should compose components to build complex UIs. Key points include:

- Component composition allows you to reuse and combine small, focused components.
- Inheritance can lead to tightly coupled code, making it harder to maintain and test.
- React's component model encourages building reusable and flexible UI components.
