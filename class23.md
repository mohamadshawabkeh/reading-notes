# Advanced State with Reducers

## Extracting State Logic into a Reducer

### Motivation for Adding a Reducer
The motivation for adding a reducer is to manage complex state logic in a more organized and maintainable manner. Reducers centralize state updates and logic, making it easier to track changes and manage application state effectively.

### Actions and their Difference from Direct State Setting
In the context of a reducer, actions are objects that describe the type of state change you want to perform. They typically have a `type` property and sometimes additional data. The key difference between using actions and setting state directly is that actions provide a standardized way to modify state, making it easier to track and manage changes. Directly setting state can lead to scattered updates and potential inconsistencies.

### Origin of the useReduce Name
The name `useReduce` is derived from the common list operation `reduce`, which involves iteratively applying a function to elements of a list to accumulate a result. Similarly, `useReducer` iterates over dispatched actions, accumulating changes to the state as per the defined logic.

### Switching from useState to useReducer
You should consider switching from `useState` to `useReducer` when your component's state logic becomes more complex and involves multiple interrelated updates. `useReducer` is especially beneficial when you find yourself passing callback functions down the component tree to update state, as it simplifies state management by encapsulating logic within a reducer function.

### return to [Main Read Me File](./README.md)
