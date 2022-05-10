# `React basics and fundamentals:`
<!-- 
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
-->
### Why React?
- React.js is a JavaScript library. It was developed by engineers at Facebook.
- React is fast. Apps made in React can handle complex updates and still feel quick and responsive.
- React is modular. Instead of writing large, dense files of code, you can write many smaller, reusable files. React’s modularity can be a beautiful solution to JavaScript’s maintainability problems.
- React is scalable. Large programs that display a lot of changing data are where React performs best.
- React is flexible. You can use React for interesting projects that have nothing to do with making a web app. People are still figuring out React’s potential. There’s room to explore.
- React is popular. While this reason has admittedly little to do with React’s quality, the truth is that understanding React will make you more employable.

### What does “syntax extension” mean?
- In this case, it means that JSX is not valid JavaScript. Web browsers can’t read it!
- If a JavaScript file contains JSX code, then that file will have to be compiled. That means that before the file reaches a web browser, a JSX compiler will translate any JSX into regular JavaScript. 

### What’s the difference between React and ReactDOM?
- React is a JavaScript library for building User Interfaces and ReactDOM is the JavaScript library that allows React to interact with the DOM.

### React basics:
- JSX (JSX is a syntax extension for JavaScript. It was written to be used with React. JSX code looks a lot like HTML)
- JSX Elements (A basic unit of JSX is called a JSX element)
- JSX elements are treated as JavaScript expressions. That means that a JSX element can be saved in a variable, passed to a function, stored in an object or array…you name it.
- Attributes In JSX (`const title = <h1 id='title'>Introduction to React.js: Part I</h1>;`)
- Nested JSX (` const theExample = (<a href="https://www.example.com"> <h1> Click me! </h1> </a>); `)
- JSX Outer Elements -> There’s a rule that we haven’t mentioned: a JSX expression must have exactly one outermost element.
###### JSX Outer Elements Example:
(`const paragraphs = (<div id="i-am-the-outermost-element"><p>I am a paragraph.</p><p>I, too, am a paragraph.</p></div>); `)
