# iNSight MicroFrontends Prettier Config
This project formats Javascript files using Prettier configuration. This will be used as a centralised formatting rules for all the 
microfrontend components.

## Purpose
[Prettier](https://prettier.io/) is an opinionated code formatter easy to configure and integrate with Code Editors. This configuration aims to quickly install and config JavaScript projects for consistent code style standards.

This package can be used as a stand-alone config or integrated with any linter. If you look to integrate with [ESLint](https://eslint.org/) for React projects take a look at our configuration [eslint-config](https://bitbucket.org/prevoirsolutionsinformatiques/eslint-config) using this Prettier config

## How to install
```
npm install prettier @prevoir/prettier-config
```
## How to use
In your `package.json` add:

```
"prettier": "@prevoir/prettier-config"
```
Under script objects
```
"format": "prettier --write \"{,!(node_modules)/**/}*.js\""
```