# React CRUD application practice

This repository is for my training of React, Redux, Node, Express and Mongo DB.

## Goal

Create a simple web application.

- Display table by using data in DB
- Search data from DB then update the table view
- Insert / delete data from client browser to DB
- Useful function provided by only copy and paste

## What is the user for

Management data such as accounts, password, firewall rules, server's IP and so on.

## Requirements

- Node
- Mongo DB

## Installing node modules

Install modules.

### Client side

```sh
yarn add react react-dom prop-types
yarn add redux
yarn add axios
```

### Server side

```sh
yarn add express
yarn add mongoose
yarn add body-parser
```

### For only developing environment

Babel is the transpiler that new ECMAScript (5 >) => ES5.
Webpack is the bundler that combine multiple JS files to one file.
Eslint is the greatest linter for JS.
babel-eslint allows us to lint all valid Babel code with the ESLint.

```sh
yarn add --dev @babel/core @babel/cli @babel/preset-env @babel/preset-react
yarn add --dev webpack webpack-cli webpack-dev-server
yarn add --dev babel-loader@8 style-loader css-loader url-loader file-loader
yarn add --dev eslint babel-eslint
```

Install Airbnb eslint config.
`npm info "eslint-config-airbnb@latest" peerDependencies` to list the peer dependencies and versions.
Then run

```sh
npm info "eslint-config-airbnb@latest" peerDependencies
yarn add --dev <dependency>@<version>
# e.g.
# yarn add --dev eslint-plugin-import@2.7.0 eslint-plugin-jsx-a11y@6.0.2 eslint-plugin-react@7.4.0
yarn add --dev eslint-config-airbnb
```
