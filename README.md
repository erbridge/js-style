# js-style

> A collection of default settings for JavaScript style checkers and linters


## Install

```
$ npm install --save-dev erbridge/js-style
```


## Setup

### JSHint

Create a `.jshintrc` file in the project root containing, for example:

```json
{
  "extends": "node_modules/js-style/jshint-node"
}
```


### JSCS

Create a `.jscsrc` file in the project root containing, for example:

```json
{
  "preset": "node_modules/js-style/jscsrc-es5.json"
}
```
