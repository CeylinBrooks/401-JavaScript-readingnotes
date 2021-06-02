Why do we not need more .html pages in a multi-page React app?

- Individual HTML pages could be found at the respective URL on the server that accurately represented the file structure 
 (i.e all blog posts were in the /blog folder). Therefore, when the browser needed the new page, it would request the new page from the server.

If we wanted a component to show up on every page, where would we put it and why?
Outside the <BrowserRouter/>
Inside the <BrowserRouter />, outside a <Route />
Inside a <Route />

- The Component needs to be wrapped Inside the <BrowserRouter /> to wrap the entire app, but outside a <Route />


What does props.children contain?

- to every component, that can be used to render the content included between the opening and closing tags when invoking a component.

Composition- a way to combine objects or data types into more complex ones. 
Common kinds of compositions are objects used in object-oriented programming, tagged unions, sets, sequences, and various graph structures

Children / Child Components- A child component is a more specific part inside a parent component.

Hash Routing- using the anchor part of the URL to simulate different content.

Link Routing- very node constructs a map of the connectivity to the network, in the form of a graph, showing which nodes are connected to which other nodes

