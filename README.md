[![circleci-status]()]()
[![node-v10.5.3](https://img.shields.io/badge/node-v10.5.3-blue.svg)](https://nodejs.org/en/)
[![yarn-v1.5.12](https://img.shields.io/badge/yarn-v1.5.12-orange.svg)](https://yarnpkg.com/en/docs/getting-started)

# SPARQL visualizer

A typescript library to simplify visualization of SPARQL queries.

## Setup

In order to take part in the development you need to setup the following tools.

### Node

You can install [nvm]() and run this command at the root of the project structure to use the required version of node

```sh
nvm install
nvm use
```

***or***

You install the node version manually specified in the `.nvmrc` file, that can 
also be found at the top of this readme file, from the [official site]().

### Yarn

Package management is done with [yarn](), for consistency use the version
from the badge specified at the top of the readme file or higher.

### Install all dependencies

***Note***: Always make sure to use the specified version of node before
developing or installing all dependencies, they are node version specific **!!!**

To download and install all dependencies to the `node_modules` folder run

```sh
yarn
```


## Development

### Scripts
You can use the following scripts to develop, test, lint, format, deploy (, ...) 
the project.

```sh
yarn start     # start the webpack development server on port 8080
yarn test      # run jest to check all test suites (*.spec.ts)
yarn lint      # lint all code with tslint
yarn prettier  # run prettier to autoformat the code
```


### Testing
Testing is performed with [Jest](). Checkout their documentation and look at
existing test suites (all files with suffix `.spec.ts`) to get you started.


## Deploy
**TODO**