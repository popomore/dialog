# rc-dialog

react dialog component

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: http://img.shields.io/npm/v/rc-dialog.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rc-dialog
[travis-image]: https://img.shields.io/travis/react-component/dialog.svg?style=flat-square
[travis-url]: https://travis-ci.org/react-component/dialog
[coveralls-image]: https://img.shields.io/coveralls/react-component/dialog.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/react-component/dialog?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/react-component/dialog.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/react-component/dialog
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/rc-dialog.svg?style=flat-square
[download-url]: https://npmjs.org/package/rc-dialog

## install

[![rc-dialog](https://nodei.co/npm/rc-dialog.png)](https://npmjs.org/package/rc-dialog)

## Usage

```js
var Dialog = require('rc-dialog');

  React.renderComponent(
      (<Dialog title={title} onClose={callback1} onShow={callback2}>
        <p>first dialog</p>
      </Dialog>),
      document.getElementById('t1')
  );
  
// use dialog
```
## API 

### property

#### visible 
  * The dialog whether or not shown,default false

#### title
  * Title of the dialog

#### onShow 
  * When the dialog shown , the callback was called.

#### onClose 
  * When the dialog closed, the callback was called.

## Development

```
npm install
npm start
```

## Test Case

http://localhost:8004/tests/runner.html?coverage

## Coverage

http://localhost:8004/node_modules/node-jscover/lib/front-end/jscoverage.html?w=http://localhost:8004/tests/runner.html?coverage




## License

rc-dialog is released under the MIT license.