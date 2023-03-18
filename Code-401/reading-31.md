# Context API

[Context API](https://reactjs.org/docs/context.html)

What can React Context provide your app?

- Context is a way to pass data through the component tree without needing to manually pass down props at every level in your application. It can provide global data that can be shared throughout React components. 

Why might we use Context?

- If we have facets of our application, such as language or region that need to be 'global' across our application

Why should we use it sparingly?

- Using context makes it harder to reuse components.

[Awesome React Context Links](https://github.com/diegohaz/awesome-react-context)

Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:

I chose to look at [React blog](https://kentcdodds.com/blog/reacts-new-context-api) and the folio library, specifically their [README](https://github.com/jalal246/folio/blob/master/README.md)

Takeaway 1:

- Context is passed through thte initial value, and returns an obj with a Provider and a Consumer.
- Provider component is used higher up in the tree and accepts a prop called value.
- Consumer component is used anywhere below the provider and accepts a prop called children which must be a function that accepts the value and return in JSX.

Takeaway 2:

- The folio library was pretty cool, in the code they use context in order to have values as a global reference. As the app runs, context states are updated with updated grid/form information. It was cool seeing context play out in this application.