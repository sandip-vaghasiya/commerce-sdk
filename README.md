# commerce-sdk

A mono repo containing the tools needed to be a rockstar commerce cloud developer.

[![CircleCI][circleci-image]][circleci-url]

## Mono repo setup

### Setup

All these commands can both be ran from the root as well as within a package in the repo.

    # To setup
    npm install

    # To run tests
    npm test

    # To build 
    npm run build


## Packages

### commerce-sdk

This is generated by the generator package and doesn't actually live in code anywhere.  Readme for this package will be in the generator package

[README](./packages/generator/README.md)

### @commerce-apps/core

This represents the core functions that call the APIs and interact with commerce cloud.  This is used by commerce-sdk

[README](./packages/core/README.md)

### @commerce-apps/exchange-connector

This is the package that communicates with exchange to download raml files to build the SDK.  This is used by the generator but not the generated sdk

[README](./packages/exchange-connector/README.md)

### Additional documentation

[Using VSCODE](./docs/vscode.md)
[Code Generation](./packages/generator/docs/GENERATOR.md)


<!-- Markdown link & img dfn's -->
[circleci-image]: https://circleci.com/gh/SalesforceCommerceCloud/commerce-sdk.svg?style=svg&circle-token=c68cee5cb20ee75f00cbda1b0eec5b5484c58b2a
[circleci-url]: https://circleci.com/gh/SalesforceCommerceCloud/commerce-sdk

