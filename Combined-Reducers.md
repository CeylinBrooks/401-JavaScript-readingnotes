Why choose Redux instead of the Context API for global state?

- easy to is use as it has a short learning curve. It requires less code, and because 
there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle.

What is the purpose of a reducer?

-  a function that determines changes to an application's state.

What does an action contain?

-  type field that tells what kind of action to perform and all other fields contain information or data.

Why do we need to copy the state in a reducer?

- state ans action arguements

immutable state- is an object whose state cannot be modified after it is created.

time travel in redux- debugging refers to the ability step forward and backward through the state of you application, 
empowering the developer understand exactly what is happening at any point in the app's lifecycle.

action creator- a function that returns an action object.

reducer- a function that determines changes to an application's state. It uses the action it receives to determine this change. 

dispatch-  a function of the Redux store
