# underscore-keypath

[![Build Status](https://travis-ci.org/jeeeyul/underscore-keypath.png?branch=master)](https://travis-ci.org/jeeeyul/underscore-keypath)

key-path mechanism extensions for underscore

```bash
$ npm install underscore-keypath
```

## How to use
```javascript
var _ = require("underscore-keypath");
```

or you may want to use origianl underscore:

```javascript
var _ = require("underscore");
require("underscore-obj"); // it will extend original underscore
```
in this case, please install "underscore" first.
```bash
$ npm install underscore underscore-obj
```

## example
```javascript
var foo = {
  bar : {
    name : "Cool!"
  }
};

_(foo).valueForKeyPath("bar.name"); // --> "Cool!"
```

see [API](https://github.com/jeeeyul/underscore-obj/wiki/API) Document
