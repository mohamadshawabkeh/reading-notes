# Redux Reading: Application State with Redux
.

## First Principle of Redux
The first principle of Redux is **"Single Source of Truth."** This means that the entire state of an application is stored in a single JavaScript object called the **"store."** This makes it easier to manage and track changes in the application's state.

## Store and Reducers
### Store
A **store** in Redux is a JavaScript object that holds the entire state of your application. It is the central place where all the data for your app is stored. The store has three main responsibilities:
1. **Holding Application State**: It holds the entire state tree of your application.
2. **Allowing Access to State**: It allows you to access the state via the `getState()` method.
3. **State Update**: It allows the state to be updated through the `dispatch(action)` method.

### Reducers
Reducers are functions in Redux that specify how the application's state changes in response to actions. They take the current state and an action as arguments and return a new state. Reducers are used within the store to update the state based on the actions dispatched by the application.

## `createStore` Methods
The `createStore` function in Redux provides several methods that are useful for managing the store:
1. **`getState()`**: This method is used to retrieve the current state of the store. It returns the current state object.

2. **`dispatch(action)`**: This method is used to dispatch an action to the store. When an action is dispatched, the store's reducers are called to update the state based on the action.

3. **`subscribe(listener)`**: The `subscribe` method allows you to register a listener function that will be called whenever the state in the store changes. It is often used to update the user interface in response to state changes.

## `combineReducers()` Function
`combineReducers` is a utility function provided by Redux. It is used to combine multiple reducer functions into a single reducer function. This is particularly useful when you have different parts of your application's state managed by different reducers. `combineReducers` creates a new reducer that delegates actions to the individual reducers and combines their results into a single state object.

 ### return to [Main Read Me File](./README.md)