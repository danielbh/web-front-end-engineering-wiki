## Front End Engineering Study Guide
A repo dedicated to solving common problems that a front end web developer encounters.

### Web

- Build the 5 most common web layouts
  - What are they? Should I use popular sites?
- Implement popular UI components
  - A datepicker with a calendar
  - An infinite scroll with loading element
  - A carrousel with animations for changing photos
  - Nav scroll component
  - type-ahead
  - vertical parrallax
  - a toast alert
  - responsive navbar
  - a gauge
  - inline input
  - responsive grid framework
  - responsive nav that closes and opens
  - Build a client-side spellchecker
- Force an image to be a specific size
- HTTP Headers
   - Cache-Control
   - ETag
   - Status Codes
   - Transfer-Encoding.
 - REST vs RPC.
 - [How to structure a REST API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)

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


### JavaScript

- Popular functions from lodash
  - debounce
  - clone
- [What is the event loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ)?
- What is the difference between a call stack and a task queue?
- ES5 class
- ES6 class
- Execution context
- lexical scope
- closures
- Hoisting, function & block scoping and function expressions & declarations.
- Binding – specifically call, bind, apply and lexical this.
- Object prototypes, constructors and mixins.
- Composition and high order functions.
- Event delegation
- Event bubbling
- How to stop event bubbling
- Type Coercion using typeof, instanceof and Object.prototype.toString.
- Handling asynchronous calls with callbacks, promises, await and async.
- When to use function declarations and expressions.
- Can you name two programming paradigms important for JavaScript app developers?
- What is the difference between classical inheritance and prototypal inheritance?
- What is asynchronous programming, and why is it important in JavaScript?
- What is a promise?
- What does 'use strict' do?
- Create a ranom number within a specified range
- [37 coding questions (Toptal)](https://www.toptal.com/javascript/interview-questions)

### CSS
- Layout – sitting elements next to each other and how to place elements in two columns vs three columns.
- Responsive design – changing an element’s dimensions based on the browser width size.
- Adaptive design – changing an element’s dimensions based on specific break points.
- Specificity – how to calculate a selector’s specificity and how the cascade affects attributes.
- Appropriate namespacing and naming of classnames.
- [Flexbox Froggy](http://flexboxfroggy.com/)
- [CSS Grid Garden](http://cssgridgarden.com/)
- What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
- Describe Floats and how they work.
- Describe z-index and how stacking context is formed.
- Describe BFC(Block Formatting Context) and how it works.
- What are the various clearing techniques and which is appropriate for what context?
- How would you approach fixing browser-specific styling issues?
- How do you serve your pages for feature-constrained browsers?
- What techniques/processes do you use?
- What are the different ways to visually hide content (and make it available only for screen readers)?
- Have you ever used a grid system, and if so, what do you prefer?
- Have you used or implemented media queries or mobile specific layouts/CSS?
- Are you familiar with styling SVG?
- Can you give an example of an @media property other than screen?
- What are some of the "gotchas" for writing efficient CSS?
- What are the advantages/disadvantages of using CSS preprocessors?
- Describe what you like and dislike about the CSS preprocessors you have used.
- How would you implement a web design comp that uses non-standard fonts?
- Explain how a browser determines what elements match a CSS selector.
- Describe pseudo-elements and discuss what they are used for.
- Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
- What does * { box-sizing: border-box; } do? What are its advantages?
- What is the CSS display property and can you give a few examples of its use?
- What's the difference between inline and inline-block?
- What's the difference between a relative, fixed, absolute and statically positioned element?
- What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
- Have you played around with the new CSS Flexbox or Grid specs?
- Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
- Have you ever worked with retina graphics? If so, when and what techniques did you use?
- Is there any reason you'd want to use translate() instead of absolute positioning, or vice-versa? And why?
- How can you clear sides of a floating element?
- How can you clear sides of a floating element?
- Does css properties are case sensitive?
- Why css selectors mixed up with cases don't apply the styles?
- Does margin-top or margin-bottom has effect on inline element?
- Does padding-top or padding-bottom has effect on inline element?
- Does padding-left or padding-right or margin-left or margin-right has effect on inline element?
- If you have a 'p' element with font-size: 10rem, will the text be responsive when the user resizes / drags the browser window?
- The pseudo class :checked will select inputs with type radio or checkbox, but not
- In a HTML document, the pseudo class :root always refers to the element.
- The translate() function can move the position of an element on the z-axis.
- Which one would you prefer among px, em % or pt and why?
   - **px**: gives fine grained control and maintains alignment because 1 px or multiple of 1 px is guaranteed to look sharp. px is not cascade, this means if parent font-size is 20px and child 16px. child would be 16px.
   - **em**: maintains relative size. you can have responsive fonts. em is the width of the letter 'm' in the selected typeface. However, this concept is tricky. 1em is equal to the current font-size of the element or the browser default. if u sent font-size to 16px then 1em = 16px. The common practice is to set default body font-size to 62.5% (equal to 10px). em is cascade
   - **%**: sets font-size relative to the font size of the body. Hence, you have to set font-size of the body to a reasonable size. this is easy to use and does cascade. for example, if parent font-size is 20px and child font-size is 50%. child would be 10px.
   - **pt**: (points) are traditionally used in print. 1pt = 1/72 inch and it is fixed-size unit.
- How absolute, relative, fixed and static position differ?
- What are the differences between visibility hidden and display none?
- What are the differences between inline, block and inline-block?
- What are the properties related to box model?
- Does overflow: hidden create a new block formatting context?
- How could you apply css rules specific to a media?
- What is the use of only?
- Does the screen keyword apply to the device's physical screen or the browser's viewport?
- What are the some pseudo classed u have used?
- How do you align a p center-center inside a div?
- How do you optimize css selectors?
- How can you load css resources conditionally?
- Why would you use sprites?
- What is specificity? How do u calculate specificity?
   - 1000 Inline styles (Presence of style in document). An inline style lives within your XHTML document. It is attached directly to the element to be styled. E.g. ```<h1 style=“color: #fff;”>```
   - 100 IDs (# of ID selectors) ID is an identifier for your page elements, such as #div.
   - 10 Classes, attributes and pseudo-classes (# of class selectors). This group includes .classes, [attributes] and pseudo-classes such as :hover, :focus etc.
   - 1 Elements and pseudo-elements (# of Element (type) selectors). Including for instance :before and :after.
- What do you know about transition?
- What are the different css filter you can use?
- What are the reasons to use preprocessor?
- Show you couple of style example and you have to tell what does it do.
- What is each side for margin x y z f ?
- How to center element css2 vs css3
  - [CSS Tricks Guide](https://css-tricks.com/centering-css-complete-guide/)
- Create a flex container
- Put flex items in a row
- Put flex items into a column
- Move flex items to the top
- Move flex items to the left
- Move flex items to the right
- Center everything
- Grow a flex item X times as big as other flex items
- Wrap flex items into multiple rows
- Wrap flex items into multiple columns
- Remove the space from wrapped rows or columns
- Pin an element to one side of the flex container
- CSS animations
- CSS sprites
- Pseudo classes
- Grid systems
- BEM and OOCSS.
- Medium CSS
- 26 CSS Questions

### Functional programming
- [What is functional programming?](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4)
- What is a pure function?
- What is functional composition?
- What is a side-effect?
- What functional programming principle does mutating something passed by reference violate?
- What are the pros and cons of functional programming vs object-oriented programming?

### Web Architecture
- Multi-device support – Will your design use the same implementation for the web, mobile web, and hybrid apps or will they be separate implementations? If you were building a site like Pinterest, you might consider three columns on the web but only one column on mobile devices. How would your design handle this?
- Asset delivery – In large applications, it’s not uncommon to have independent teams owning their own codebases. These different codebases probably have dependencies on each other and each usually has their own pipeline to release changes to production. Your design should consider how assets are built with dependencies (code splitting), tested (unit and integration tests) and deployed. You should also think about how you will vend assets through a CDN or inline them to reduce network latency.
- Rehydrating
- Advantages and Disadvantages of a SPA versus a web page
- What are two-way data binding and one-way data flow, and how are they different? You should also think about if your design will follow a passive or reactive programming model, and how components related to each other for example Foo–> Bar or Foo –>Bar.
- What are the pros and cons of monolithic vs microservice architectures?
- Rendering – client-side (CSR), server-side (SSR) and universal rendering.
- Layout – if you’re designing a system used by multiple development teams, you need to think about building components and if you require teams to follow a consist markup to use said components.
- Async flow – your components may need to communicate in real-time with the server. The design you propose should consider XHR vs bidirectional calls. If your interviewer asks you to support older browsers, your design will need to choose between hidden iFrames, script tags or XHR for messaging. If not, you could propose using websockets or you might decide server-sent events (SSE) are better.

### General Architecture
- When is classical inheritance an appropriate choice?
- When is prototypal inheritance an appropriate choice?
- What does “favor object composition over class inheritance” mean?
- Separation of concerns
  - MVC
  - MVVM
  - MVP
- Why might you create static class members
- Decorator
- Factory
- Singleton
- Revealing module
- Facade
- Observer

### Performance
- Critical rendering path.
- Service workers.
- Image optimizations.
- Lazy loading and bundle splitting.
- General implications of HTTP/2 and server-push.
- When to prefetch and preload resources.
- Reduce browser reflows and when to promote an element to the GPU.
- Differences between the browser layout, compositing and painting.
- What are some ways you may improve your website's scrolling performance?
- What tools would you use to find a performance bug in your code?
- [Front End Performance Checklist](https://hackernoon.com/front-end-performance-check-list-for-production-4e930cb63e8a)

### Security
  - JSONP
  - CORS
  - iFrame policies.
  - [OWASP top 10](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/owasptop10/OWASP%20Top%2010%20-%202013.pdf)
  - [Security Checklist](https://blog.hartleybrody.com/startup-security/)

### React/Redux/MobX/GraphQL
- [Build React from scratch and explain each part](https://github.com/danielbh/didact)
- Why would you use React as opposed to something else? Benefits? Cons?
- Why would you use Redux or MobX?
- Why would you use GraphQL?
- How to create Redux Middleware
- What is React Fiber?
- [Virtual & Shadow DOM](https://stackoverflow.com/questions/36012239/is-shadow-dom-fast-like-virtual-dom-in-react-js)

### General Questions
- What is your general approach to fixing things that are broken?
- What UI component have you tried that didn't work out.

### Basic Algorithms
- [55 Algo Expert Questions](https://www.algoexpert.io/questions)
- Quicksort
- Merge sort
- Breadth First Search
- Depth First Search
- BST Traversal (in-order, pre-order, post-order)
- Binary Search
- Fibonacci Recursive Memoized
- Fibonacci Iterative

### Data Structures
- Hashmap
- Linked List
- Binary Search Tree
- Tree
- Trie
- Min Heap

### Developer Tools
- [Merging vs Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)
- [A Quick Tutorial on Git Rebasing](https://benmarshall.me/git-rebase/)
- [Git Rebase example](https://repl.it/@danielbh/Git-Rebase-Example)

## References

- [David Shariff's Perparing for a Front-End Web Development Interview 2017](http://davidshariff.com/blog/preparing-for-a-front-end-web-development-interview-in-2017/#first-article)
- [Eric Elliot's 10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [That JS Dude](https://github.com/khan4019/front-end-Interview-Questions)
- [FE Interview Handbook](https://github.com/yangshun/front-end-interview-handbook)

