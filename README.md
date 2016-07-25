# objects-node

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
  property1: '...',
  property2: 123,
  property3: true
});
```


## License

MIT
