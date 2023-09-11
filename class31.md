# Readme.md - Redux Combined Reducers

### Multiple Reducers Example

**Q1: Why create multiple reducers?**
A1: Multiple reducers are created to manage different slices of the application state separately. This allows for better organization and maintainability of your Redux store as your app grows.

**Q2: How would you combine multiple reducers?**
A2: You can combine multiple reducers using the `combineReducers` function provided by Redux. This function allows you to create a single root reducer that delegates actions to specific sub-reducers.

**Q3: How will you manage state as an immutable object? Why?**
A3: State is managed as an immutable object in Redux to ensure predictability and maintain the purity of reducer functions. Immutability helps in tracking changes, debugging, and maintaining the application's state over time.

### Redux Docs: Using Combined Reducers

**Q4: combineReducers is a utility function to simplify the most common use case when writing ___ _____.**
A4: combineReducers is a utility function to simplify the most common use case when writing Redux reducers.

**Q5: Explain how combineReducers assembles the new state tree.**
A5: `combineReducers` assembles the new state tree by calling each reducer with the current state and the action being dispatched. It then combines the results into a new state object.

**Q6: How would you define initial state in an app using combineReducers?**
A6: To define initial state in an app using `combineReducers`, you can provide an initial state object as the default value for each reducer's state parameter.

### Redux Docs: Combined Reducer Syntax

**Q7: Why will you want to split your reducing functions as your app becomes more complex?**
A7: As your app becomes more complex, you may want to split your reducing functions to manage different parts of the state separately. This improves code organization and maintainability.

**Q8: The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**
A8: The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to the Redux store.

**Q9: What is a popular convention when naming reducers?**
A9: A popular convention when naming reducers is to name them after the slice of state they manage. For example, if a reducer manages the user's authentication state, it might be named `authReducer`.

 ### return to [Main Read Me File](./README.md)
