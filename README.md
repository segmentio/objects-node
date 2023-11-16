# objects-node [![Build Status](https://travis-ci.org/segmentio/objects-node.svg?branch=master)](https://travis-ci.org/segmentio/objects-node) [![npm version](https://badge.fury.io/js/objects-node.svg)](https://badge.fury.io/js/objects-node)

> **Note**  
> Segment has paused maintenance on this project, but may return it to an active status in the future. Issues and pull requests from external contributors are not being considered, although internal contributions may appear from time to time. The project remains available under its open source license for anyone to use.

  Node.js client for Segment Objects API


## Setup

To install,

`npm install --save objects-node`

Then, in your code,

```js
var Objects = require('objects-node');
var objects = new Objects('<your write key>')
```


## Usage

```js
objects.set('<collection>', '<id>', {
  some_property: 'some value',
  name: 'Schrodinger',
  is_alive: true,
  is_dead: true,
  owner: 'Erwin',
  birth_year: 1935
});
```


## License

MIT
