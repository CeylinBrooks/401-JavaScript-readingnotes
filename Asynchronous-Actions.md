How granular should your reducers be?

-  granularity is good and valuable because different reducers, different parts of your application might need to react differently to those actions.

Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

- Con, multiple actions inside of the field it fires your action that in turn changes the state via reducer

Name a strategy for preventing the above?

- the use of middleware will prevent the above issue

store- holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it.

combined reducers- helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

