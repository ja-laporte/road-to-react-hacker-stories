# I am learning react through the use of the book 'The Road To React' by Robin Wieruch

# These notes are just a way to see if I understand. It isn't to be taken as gospel, as I am just trying to deconstruct what's in the book and repeat back what I (think) I know.

I'll be going through each section of the book and push to GitHub as I progress.

I'll be taking notes as a go, for better retention (hopefully) of the material.

Fundamentals of React:

- Setting up a React Project => use npx create-react-app <project name>
  -create-react app is can be used to quickly creating a project as a starter-kit. The focus is to have a project that doesn't require a dev to spend to much time setting up a project, and instead dive straight into coding.
  - The src/App.js is where React components are used to build out your application. Components can be broken down into their own files within src/. This provides separations of concern.
- The React Component:
  -A component is just a JavaScript function(or class) and can have parameters passed into it called props
  -A component returns code that looks like HTML but is actually JSX.
  -JSX is just a way to inject HTML with JS capabilities all bundled up.
  -A Function component will run when it is rendered for the first time(called?) or updated at some point.
  -Rendering means to display something in the browser.
  **NOTE**
  If a variable doesn't need anything from the component, it can be defined outside of the component. This will define it once, and not each time the function is called.
  -JSX uses a camelCase version of HTML for its attributes (ex. class is className in JSX)
  -JSX can be used to execute functions and expressions
  -To render an array to the browser can be done using map: return arr.map(item => <p>{item}<p>)
  -To render an item from an array of objects: return arr.map(item => <p>{item.title}<p>)
  -This can be used to extract information to be rendered.
  -When iterating over an array of objects and rendering them, you should use a key attribute to each list item's element. This helps if/when list items get re-ordered, they each have a unique identifier. Some data will already have this available, but it should be best practice to assign one if none are given.
  -Null is allowed in JSX and is used if/when you don't want anything rendered.
  -Component Hierarchies:
  -App is the root component because it renders all other components that makeup the application
  -The other components that are rendered by App are children components, and they can themselves be parent components of components they render.
  -A component is considered a leaf component when it doesn't render any components.

---

Pausing where note taking needs to pick back up:

# React Definition
