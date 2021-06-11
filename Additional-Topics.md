What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

- The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount )
of a Higher Order Component that wraps your app.

[Link](https://stackoverflow.com/questions/39356517/correct-way-to-pre-load-component-data-in-reactredux#:~:text=1%20Answer&text=The%20most%20'redux%2Dlike',Component%20that%20wraps%20your%20app.)

When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

- The dispatched action updateDone mutates state before post and profile data are in the store. 
This makes async/await unpredictable since we don't know when a dispatch with response data executes.

[Link](https://blog.jscrambler.com/async-dispatch-chaining-with-redux-thunk/)


middleware- software that lies between an operating system and the applications running on it

thunk- middleware that allows you to return functions, rather than just actions, within Redux
