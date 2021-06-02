What does a component’s lifecycle refer to?

- Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle.
[Link](https://www.freecodecamp.org/news/how-to-understand-a-components-lifecycle-methods-in-reactjs-e1a609840630/#:~:text=We%20are%20born%2C%20grow%2C%20and,to%20as%20a%20component%20lifecycle.)

Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect?

- useCallback will help in avoiding regeneration of functions when the functional component re-renders. 
However there isn't much of a performance difference caused by recreation of functions.

Why are functional components preferred over class components?

- to read and test because they are plain JavaScript functions without state or lifecycle-hooks

What is wrong with the following code?

import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (<div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}

^ In the code above, the useEffect would realize in an infinite loop.

state hook- a special function that lets you “hook into” React features.

effect hook-  lets you perform side effects in function components:

reducer hook- a reducer of type (state, action) => newState, 
and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.)
