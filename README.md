[![npm version](https://badge.fury.io/js/sd-mock-server.svg)](https://badge.fury.io/js/sd-mock-server)
[![Build Status](https://travis-ci.org/staticdeploy/sd-mock-server.svg?branch=master)](https://travis-ci.org/staticdeploy/sd-mock-server)
[![Coverage Status](https://coveralls.io/repos/github/staticdeploy/sd-mock-server/badge.svg?branch=master)](https://coveralls.io/github/staticdeploy/sd-mock-server?branch=master)
[![Dependency Status](https://david-dm.org/staticdeploy/sd-mock-server.svg)](https://david-dm.org/staticdeploy/sd-mock-server)
[![devDependency Status](https://david-dm.org/staticdeploy/sd-mock-server/dev-status.svg)](https://david-dm.org/staticdeploy/sd-mock-server#info=devDependencies)

# sd-mock-server

Easy to use, no frills mock server.

## Install

```sh
npm i --save-dev sd-mock-server
```

## Usage

* create a directory `mock-server`
* place some handler files in it
* run `sd-mock-server`

## CLI options

* `root`: mock server root directory, defaults to `mock-server`
* `port`: mock server port, defaults to `3456`
* `delay`: milliseconds to delay responses by, defaults to 0
* `watch`: boolean flag, makes the server reload on file changes