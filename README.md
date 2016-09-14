# brian-react-yo-1
> Generator-React-Webpack - with Flux Support (using Redux)

[![Build Status](https://travis-ci.org/stylesuxx/generator-react-webpack-redux.svg?branch=master)](https://travis-ci.org/stylesuxx/generator-react-webpack-redux) ![Amount of Downloads per month](https://img.shields.io/npm/dm/generator-react-webpack-redux.svg "Amount of Downloads") [![Dependency Status](https://david-dm.org/stylesuxx/generator-react-webpack-redux.svg)](https://david-dm.org/stylesuxx/generator-react-webpack-redux) [![devDependency Status](https://david-dm.org/stylesuxx/generator-react-webpack-redux/dev-status.svg)](https://david-dm.org/stylesuxx/generator-react-webpack-redux?type=dev) ![Node Version](https://img.shields.io/node/v/generator-react-webpack-redux.svg "Node Version")

## What is it for?
This generator can be used to create and manage projects that use React, Webpack and Flux (using [Redux](https://github.com/rackt/redux) as implementation). It depends on [generator-react-webpack](https://github.com/newtriks/generator-react-webpack) as a base and extends it to create new reducers and actions.

## What is included?
generator-react-webpack-redux includes support for creating new reducers (and tests), as well as the creation of actions and components.

It also has support for the the features that are available in its parent project, generator-react-webpack. This includes the run-configuration, webpack, esLint and test-environment.

## Planned Features and updates
There are currently some features missing from the generator. These will be available in a later version:

- [ ] Add optional routing via [react-router-redux](https://github.com/rackt/react-router-redux)
- [ ] Route generator

## Requirements
Make sure your nodeJS version is **>=4.5** and npm  version is **>=3.0.0**.

## Installation
```bash
npm install -g yo
npm install -g brian-react-yo-1
```

### Global npm packages
Install the following packages system wide, to decrease the time needed to scaffold a new project:
```bash
npm install -g phantomjs-prebuilt
```

## Setting up projects
```bash
# Create a new directory, and `cd` into it:
mkdir my-new-project && cd my-new-project

# Run the generator
yo brian-react-yo-1
```

## Generating new reducers
```bash
yo brian-react-yo-1:reducer my/namespaced/reducers/name
yo brian-react-yo-1:reducer items
```

## Generating new actions
```bash
yo brian-react-yo-1:action my/namespaced/actions/name
yo brian-react-yo-1:action addItem
```

## Generating new components
```bash
yo brian-react-yo-1:component my/namespaced/components/name
yo brian-react-yo-1:component button
```

## Generating new containers
```bash
yo brian-react-yo-1:container my/namespaced/container/Name
yo brian-react-yo-1:container wrapper
```

## Usage
Please take a look at [react-webpack-template](https://github.com/weblogixx/react-webpack-template) for an in depth explanation or use `npm run` to get a list of all commands available for building and running your application.

Basics are:
- `npm start`: Will start up the dev webserver
- `npm test`: Run unit tests
- `npm run dist`: Create the packed version

## Contribute
Contributions are welcome. If you find something is missing or there are errors hidden somewhere, feel free to add a new issue.

If you want to submit a pull request please do so from and against the *develop* branch.

### Running Tests
`npm test` or `node node_modules/.bin/mocha`

## License
[MIT license](http://opensource.org/licenses/MIT)

