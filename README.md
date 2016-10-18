# Cache Warmer

This package represents the top 500 dependencies on npm according to [https://www.npmjs.com/browse/depended](https://www.npmjs.com/browse/depended).

## Usage
Simply install and then remove with your favorite package manager.

### Yarn

```
yarn add big-bertha && yarn remove big-bertha
```

### NPM

```
npm install -g big-bertha && npm uninstall -g big-bertha
```

# Contributing

Packages are added or removed based on how often they're dependend upon from other npm packages. This repository currently indexes the top 500.

If a package has external requirements to install, it will not be included on the list. Examples include: [canvas](https://github.com/Automattic/node-canvas), [zqm](https://github.com/JustinTulloss/zeromq.node)
