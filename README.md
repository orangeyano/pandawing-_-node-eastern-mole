# Eastern Mole

**Eastern Mole** aims to be the simplest API-centric Flux app one could build using React.

Currently, it uses :

* [React 0.13.x](http://facebook.github.io/react/) with [JSX](https://facebook.github.io/jsx/);
* [Geiger](https://github.com/netgusto/geiger), a tiny flux implementation (&lt;50 SLOC) with Dependency Injection features;
* [React-Router](https://github.com/rackt/react-router) for the routing;
* [Immutable.js](http://facebook.github.io/immutable-js/) for immutability in the stores;
* [Babel](https://babeljs.io/) for ES6/ES7 transpilation and linting;
* [Webpack](http://webpack.github.io/) for the tooling.
* [IdiomaticReact](https://github.com/netgusto/IdiomaticReact), simple sample app.

## Install & run

```
git clone https://github.com/pandawing/eastern-mole
cd eastern-mole
npm install
grunt serve
```

Then navigate to [http://localhost:8000]()

## License

### Eastern Mole

Copyright (c) 2015 sanemat [Licensed under the MIT license](./LICENSE.txt)

### IdiomaticReact

Copyright (c) 2015 Jérôme Schneider / Net Gusto [Licensed under the MIT license](./LICENSE-IdiomaticReact.txt)
