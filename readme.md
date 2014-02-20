*This repository is a mirror of the [component](http://component.io) module [ramitos/resize](http://github.com/ramitos/resize). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-resize`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# resize

resize event for any DOM element with polling. [demo](http://ramitos.github.com/resize)

## install

```bash
$ component install ramitos/resize
```

## example

```js
var resize = require('resize');

resize.bind(document.getElementById('mytextarea'), function () {});
```

## api

#### bind(element, callback[, pollingInterval])

`pollingInterval` default is `250ms`

#### unbind(element, callback)

## license

MIT