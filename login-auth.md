Why is the Context API useful?

- a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application

Can a component outside of a provider get its context?

- context in functional components by making use of useContext hook

What are some common use cases for using the Context API?

- Themes, Multilingual application, Authorisation: setting the user role and info

Describe “Context Hell” - it seems code that is hodge podge of a whole bunch of children that needs to be sorted out but that will take some doing.

global state- state decalred a the globally scoped level

global context- designed to share data that can be considered “global” for a tree of React components, 
such as the current authenticated user, theme, or preferred language

provider- component makes the Redux store available to any nested components that need to access the Redux store.


consumer- are descendants of a Provider will re-render whenever the Provider’s value prop changes
