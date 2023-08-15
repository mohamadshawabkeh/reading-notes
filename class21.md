# useState() Hook

## Thinking in React: Five Steps

1. **Break the UI into a Component Hierarchy**: Divide the UI into smaller, reusable components to organize and simplify the structure.

2. **Build a Static Version**: Create a non-interactive version of the UI using components and props to visualize the layout.

3. **Identify the Minimal UI State**: Determine the necessary data that needs to be stored in the state to reflect the UI's dynamic behavior.

4. **Identify Where State Should Live**: Decide which component should manage the identified state, considering the data flow and component responsibilities.

5. **Add Inverse Data Flow**: Establish data flow by passing callbacks from parent to child components, allowing child components to modify the parent's state.


## State: A Component’s Memory

- **Limited Local Variables**: Why are local variables insufficient for managing a React component's state?

- The **argument to the useState hook**: What is the purpose of the argument passed to the useState hook, and what does the returned array contain?

- **Accessing state from Component A to Component B**: How can Component A access and interact with the state managed by Component B in React?

### return to [Main Read Me File](./README.md)