# `React basics and fundamentals:`

### Rendering JSX:
```
import React from 'react';
import ReactDOM from 'react-dom';
ReactDOM.render(<h1>Hello world</h1>, document.getElementById('app'));
```
### Basic Info
- ReactDOM is the name of a JavaScript library.
- This library contains several React-specific methods, all of which deal with the DOM in some way or another.

### Let's Analyze The Code:
- ReactDOM is the name of a JavaScript library. This library contains several React-specific methods, all of which deal with the DOM in some way or another.
- ReactDOM.render() is the most common way to render JSX. It takes a JSX expression, creates a corresponding tree of DOM nodes, and adds that tree to the DOM. That is the way to make a JSX expression appear onscreen.
- `<h1>Hello world</h1>` This is the first argument being passed to ReactDOM.render(). 
- ReactDOM.render()‘s first argument should be a JSX expression, and it will be rendered to the screen.
- see this expression: `document.getElementById('app')`



