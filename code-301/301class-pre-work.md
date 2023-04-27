# Prep: Dive Into React

* [WEB](https://www.youtube.com/watch?v=FRjlF74_EZk)

* [REPO](https://github.com/danielquilo/readings-notes-v1)

# What is React?
React is an Agnostic User
A User interface Library
a robust JavaScript library used in dynamic web application development.

# What is a component?

[Components and Props](https://legacy.reactjs.org/docs/components-and-props.html)
Component Architecture
A React class component is a native JavaScript class, so it inherited the issues of JavaScript classes, including working with this, explicitly binding methods, verbose syntax, and more.  

# What is the dataflow of React?

[Data flows down one way though a React app.](https://www.letsreact.org/data-flow-in-react/)

As our project grows, the main thing we need to achieve is to pass data from one component to other for communication between components. React uses unidirectional data flow for passing the data between the components.
As the project grows, we need to pass data between the components, which can either be from parent to children, children to parents, or between siblings. To pass data from parent to children we need to use read-only props, to pass data from children to parent we need to use call back, and to pass data between siblings we need the combination of both.

# How do we make a React element a DOM element?

[Introduction a React Element](https://www.freecodecamp.org/news/react-interview-question-what-gets-rendered-in-the-browser-a-component-or-an-element-1b3eac777c85/#:~:text=A%20React%20Element%20is%20what,object%20that%20the%20function%20returns.) A React Element is what gets returned from components. It's an object that virtually describes the DOM nodes that a component represents. With a function component, this element is the object that the function returns.
[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web. This guide will introduce the DOM, look at how the DOM represents an HTML document in memory and how to use APIs to create web content and applications.

# React is a User Interface ______.?

[React ](https://legacy.reactjs.org/)
React is a JavaScript library for building user interfaces. It lets you compose a complex UI from small and isolated pieces of code called “components”. You can think of components as custom, reusable HTML elements with content (or data) that can be changed without reloading the entire page.

# Which direction does data flow in React?

In React JS, data flows in one direction, from Parent to Child. This helps components to be simple and predictable.

# very component manages its own ____.?

 * Own properties and local state. 

[React Components, Elements, and Instances](https://legacy.reactjs.org/blog/2015/12/18/react-components-elements-and-instances.html)

 If you’re new to React, you probably only worked with component classes and instances before. For example, you may declare a Button component by creating a class. When the app is running, you may have several instances of this component on screen, each with its own properties and local state. This is the traditional object-oriented UI programming. Why introduce elements?

In this traditional UI model, it is up to you to take care of creating and destroying child component instances. If a Form component wants to render a Button component, it needs to create its instance, and manually keep it up to date with any new information.