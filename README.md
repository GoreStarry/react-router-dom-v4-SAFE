# react-router-dom

DOM bindings for [React Router](https://reacttraining.com/react-router).

Only upgrade by

```
npx react-codemod rename-unsafe-lifecycles --force
```

## Installation

Using [npm](https://www.npmjs.com/):

    $ npm install --save react-router-dom

Then with a module bundler like [webpack](https://webpack.github.io/), use as you would anything else:

```js
// using ES6 modules
import { BrowserRouter, Route, Link } from "react-router-dom";

// using CommonJS modules
var BrowserRouter = require("react-router-dom").BrowserRouter;
var Route = require("react-router-dom").Route;
var Link = require("react-router-dom").Link;
```

The UMD build is also available on [unpkg](https://unpkg.com):

```html
<script src="https://unpkg.com/react-router-dom/umd/react-router-dom.min.js"></script>
```

You can find the library on `window.ReactRouterDOM`.

## Issues

If you find a bug, please file an issue on [our issue tracker on GitHub](https://github.com/ReactTraining/react-router/issues).

## Credits

React Router is built and maintained by [React Training](https://reacttraining.com).
