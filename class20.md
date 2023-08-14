#  Component Based UI

## Building Blocks of a React App

**Question**: What are the building blocks of a React app?
**Answer**: The building blocks of a React app include components, props, state, and JSX.

## Difference Between HTML Element and React Component

**Question**: What is the difference between an HTML element and a React component?
**Answer**: An HTML element represents a DOM element, while a React component is a reusable UI piece composed of elements, logic, and functionality.

## JSX and Its Usage

**Question**: What is JSX and why do we use it?
**Answer**: JSX stands for JavaScript XML. It's a syntax extension used in React to write HTML-like code in JavaScript, making code more readable and concise.

## Embedding JavaScript Expressions in JSX

**Question**: Describe the process of embedding JavaScript expressions in JSX.
**Answer**: JavaScript expressions can be embedded in JSX using curly braces `{}`. For example: `{variable}`, `{2 + 2}`, etc.

## Iteration and Conditional Logic in React

**Question**: Does React or JSX have any special features for iteration or conditional logic?
**Answer**: Yes, React provides the `map` function for iteration and supports conditional rendering using `if` statements or the ternary operator in JSX.

## Responding to User Inputs in React

**Question**: How does React know to respond to a user’s inputs?
**Answer**: React responds to user inputs using event handlers like `onClick`, `onChange`, etc. These handlers trigger component updates, leading to UI changes.

## React Components and Hooks

**Question**: What word indicates that a React component manages data with a Hook?
**Answer**: The term indicating that a React component manages data with a Hook is `useState`.

**Question**: How can two React components share data?
**Answer**: Data sharing between React components is achieved through props and a unidirectional data flow. Parent components pass data to child components via props.

## Render and Commit

**Question**: What are the three steps of refreshing a React UI?
**Answer**: The three steps of refreshing a React UI are: Data changes in the component's state or props, the `render()` method is called, and React compares the new and previous virtual DOM, updating the actual DOM.

**Question**: How do you trigger updates to a component after the initial render?
**Answer**: After the initial render, you can trigger updates to a component's state using the `setState()` method. This re-renders the component and reflects the updated state in the UI.

**Question**: Does React recreate DOM nodes on every rerender?
**Answer**: No, React does not recreate DOM nodes on every re-render. It intelligently updates only the necessary parts of the DOM to reflect the changes in the virtual DOM.

**Question**: After React has updated the DOM, what still needs to happen before the user sees the change?
**Answer**: After React updates the DOM, the browser's layout and painting processes need to occur before the user sees the actual changes. This involves calculating element positions and rendering them on the screen.
