# This is how React Works

- Root:

  The index.html file inside the public directory, contains a div id="root" that is take at index.js and contains the entire code. This root element, in the index.js, renders the App Component, which is the main component that will display the entire website.

- A component is javascript function that returns a UI in html.
- JSX = HTML + JS -> You can put a JS code at the HTML element inside {}.
- To return a component you need to call the function inside a self closed tag: <User/>

- Props:

  Every react component will accept a argument that is a object called props. This props will represent all the data that we may want to pass to the component, and can be passed to another component.

- useState:

  In React, the state is data or properties you can use in our application. States are mutable, meaning their value can change, and for that, the useState() hook is used to handle and manage your states. The useState() hook allows you to create, track and update a state in functional components. To use the useState() hook, you must first import it from React, or you will have to append it like React.useState() anytime you have to create a state. useState() hook does not return just a variable, as seen above, but it also returns a second value, a function that you can use to update the state value.

  const [state, setState] = useState(initialState);

- Component Lifecycle:

  1. mounting
  2. updating
  3. unmonting
