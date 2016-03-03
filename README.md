# npm_module

This repository contains a basic npm module that you can clone and start using right away. The goal is to include the minimum necessary parts that every module is going to use. That's why this is not including any test framework.

## Tools

We include a set of tools that are useful for us on a day-to-day basis.

- Webpack -> Bundles the application in one final module.
- Babel -> Transpiles the ES6 (or ES2015) to ES5.
- ESLint with the Standard syntax -> This is our linter of choice for checking the code style. There is a small tweak to request trailing commas. Because we love trailing commas :)

### Install dependencies

`npm install`

### Build the module

`npm build`

### Publish to npm

`npm publish`
