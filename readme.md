# Event emitter

## Install

```sh
npm install mevent --save
```

## Use

```js
const hub = require('mevent')()

hub.on('ping', arg => console.log(arg))

hub.emit('ping', 'hi!')
```
