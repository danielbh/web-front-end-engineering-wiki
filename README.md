## Front End Engineering Study Guide
A repo dedicated to interview preparation for a front-end developer

### Web

- Build the 5 most common web layouts
  - What are they? Should I use popular sites?
- Implement popular UI components
  - A datepicker with a calendar
  - An infinite scroll with loading element
  - A carrousel with animations for changing photos
  - Nav scroll component
  - Force an image to be a specific size

### DOM

- Selecting or finding nodes using document.querySelector and in older browsers document.getElementsByTagName.
- Traversal up and down – Node.parentNode, Node.firstChild, Node.lastChild and Node.childNodes.
- Traversal left and right – Node.previousSibling and Node.nextSibling.
- Manipulation – add, remove, copy, and create nodes in the DOM tree. You should know operations such as how to change the text content of a node and toggle, remove or add a CSS classname.
- Performance – touching the DOM can be expensive when you have many nodes, you should at least know about document fragments and node caching.

### HTML

- Semantic markup.
- Tag attributes, such as disabled, async, defer and when to use data-*.
- Knowing how to declare your doctype (most people are not writing new pages every day and forget this) and what meta tags are available to use.
- Accessibility concerns, for example, making sure an input checkbox has a larger responding area (use label “for”). Also, role=”button”, role=”presentation”, etc.

### CSS
- Layout – sitting elements next to each other and how to place elements in two columns vs three columns.
- Responsive design – changing an element’s dimensions based on the browser width size.
- Adaptive design – changing an element’s dimensions based on specific break points.
- Specificity – how to calculate a selector’s specificity and how the cascade affects attributes.
- Appropriate namespacing and naming of classnames.
- [Flexbox](http://flexboxfroggy.com/)
- [CSS Grid](http://cssgridgarden.com/)

### JavaScript

- Popular functions from lodash
  - debounce
  - clone
- Execution context, especially lexical scope and closures.
- Hoisting, function & block scoping and function expressions & declarations.
- Binding – specifically call, bind, apply and lexical this.
- Object prototypes, constructors and mixins.
- Composition and high order functions.
- Event delegation
- Event bubbling
- Type Coercion using typeof, instanceof and Object.prototype.toString.
- Handling asynchronous calls with callbacks, promises, await and async.
- When to use function declarations and expressions.
- Can you name two programming paradigms important for JavaScript app developers?
- What is the difference between classical inheritance and prototypal inheritance?
- What is asynchronous programming, and why is it important in JavaScript?
- What is a promise?

### Architecture / System Design
- When is classical inheritance an appropriate choice?
- What are the pros and cons of functional programming vs object-oriented programming?
- What is functional programming?
- When is prototypal inheritance an appropriate choice?
- What does “favor object composition over class inheritance” mean?
- What are two-way data binding and one-way data flow, and how are they different? You should also think about if your design will follow a passive or reactive programming model, and how components related to each other for example Foo–> Bar or Foo –>Bar.
- What are the pros and cons of monolithic vs microservice architectures?
- What is a pure function?
- What is functional composition?
- Rendering – client-side (CSR), server-side (SSR) and universal rendering.
- Layout – if you’re designing a system used by multiple development teams, you need to think about building components and if you require teams to follow a consist markup to use said components.
- Async flow – your components may need to communicate in real-time with the server. The design you propose should consider XHR vs bidirectional calls. If your interviewer asks you to support older browsers, your design will need to choose between hidden iFrames, script tags or XHR for messaging. If not, you could propose using websockets or you might decide server-sent events (SSE) are better.
- Separation of concerns
  – MVC
  - MVVM
  - MVP
- Multi-device support – Will your design use the same implementation for the web, mobile web, and hybrid apps or will they be separate implementations? If you were building a site like Pinterest, you might consider three columns on the web but only one column on mobile devices. How would your design handle this?
- Asset delivery – In large applications, it’s not uncommon to have independent teams owning their own codebases. These different codebases probably have dependencies on each other and each usually has their own pipeline to release changes to production. Your design should consider how assets are built with dependencies (code splitting), tested (unit and integration tests) and deployed. You should also think about how you will vend assets through a CDN or inline them to reduce network latency.
- Rehydrating

### Performance
- Critical rendering path.
- Service workers.
- Image optimizations.
- Lazy loading and bundle splitting.
- General implications of HTTP/2 and server-push.
- When to prefetch and preload resources.
- Reduce browser reflows and when to promote an element to the GPU.
- Differences between the browser layout, compositing and painting.

### React
- [Build React from scratch and explain each part](https://github.com/danielbh/didact)
- Why would you use React as opposed to something else? Benefits? Cons?
- Why would you use Redux or MobX?
- What is React Fiber?
- What is the Shadow DOM?

### Creative Problem Solving
- What is your general approach to fixing things that are broken?

## References

- [David Shariff's Perparing for a Front-End Web Development Interview 2017](http://davidshariff.com/blog/preparing-for-a-front-end-web-development-interview-in-2017/#first-article)
- [Eric Elliot's 10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

