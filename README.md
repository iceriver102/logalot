# imagemin-log [![Build Status](http://img.shields.io/travis/imagemin/imagemin-log.svg?style=flat)](https://travis-ci.org/imagemin/imagemin-log)

> The log utility used in imagemin related projects

## Install

```sh
$ npm install --save imagemin-log
```

## Usage

```js
var log = require('imagemin-log');

log.info('this is a message');
log.warn('this is a warning');
log.success('this is a success message');
log.error(new Error('this is a error').stack);

/*
     info : this is a message
     warn : this is a warning
  success : this is a success message
    error : this is an error

    at ChildProcess.exithandler (child_process.js:648:15)
    at ChildProcess.emit (events.js:98:17)
 */
```

## License

MIT © [Kevin Mårtensson](https://github.com/kevva)
