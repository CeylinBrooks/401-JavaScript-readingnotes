Describe use cases for useMemo() and useReducer().

- takes three positional arguments — a reducer, its initial state, and a function that can return the initial state (Reducer)
- similar to useCallback except that instead of memoizing a function, it memoizes a value.

Why do custom hooks need the use prefix?

- Its name should always start with use so that you can tell at a glance that the rules of Hooks apply to it


What do custom hooks usually do?

- allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.


Using any list of custom hooks, research and name one that you think will be useful in your applications?

- useCallback, because it essentially restarts the function.


Describe how a hook that fetches API data might work

- First, we're going to import stuff we're going to use and create a function. 
- The next step is to add a useState hook and to define the name of the state - in our case, that's data. 
- Then, we define the function we'll use later on to update the state - setData

reducer- a function that determines changes to an application's state.
