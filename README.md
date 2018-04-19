# vue-generate-cli

A cli tool for auto-generating vue template component.

### Installation

Prerequisites: [Node.js](https://nodejs.org/en/) (>=4.x, 6.x preferred), npm version 3+ and [Git](https://git-scm.com/).

``` bash
$ npm install -g vue-generate-cli
or
$ yarn global add vue-generate-cli
```

### Usage

``` bash
// default generate a new file in components directory
$ vue-g g <filename>
or
// generate a new file in custom directory
$ vue-g g <dirname> <filename>
or
// generate more new files in custom directory
$ vue-g g <dirname> <filename01> <filename02> <filename03> <filename(2N+1)>
```

Example:

``` bash
$ vue-g g my-component
or
$ vue-g g libs my-component
or
$ vue-g g libs my-component01 my-component02 my-component03
```