Do child components have direct access to props/state from the parent?

- no way to pass props from a child component to a parent component. However, we can always pass around functions from the parent to child component.

[Link](https://www.pluralsight.com/guides/how-to-pass-props-object-from-child-component-to-parent-component)

When a component “wraps” another component, how does the child component’s output get rendered?

- The first parameter is the wrapped component. The second parameter retrieves the data we’re interested in, given a DataSource and the current props.

[Link](https://reactjs.org/docs/higher-order-components.html)

Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?

- Yes,  React application on whether you want to use the generic Form component (e.g. Form) or s
- pecialize it as standalone Form component with a special use case (e.g. UsernameForm).

[Link](https://www.robinwieruch.de/react-component-composition)

What trick can a parent use to share all props with it’s children?

- props from parent to child at once, you need to take advantage of the spread operator

props.children- components that represent ‘generic boxes’ and that ‘don’t know their children ahead of time’.

composition- or mechanism to combine simple functions to build more complicated ones

