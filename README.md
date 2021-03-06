# @popjs/util

[popjs-util](https://github.com/imvkmark/popjs-util)

[![](https://img.shields.io/badge/Powered%20by-jslib%20base-brightgreen.svg)](https://github.com/yanhaijing/jslib-base)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/imvkmark/popjs-util/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/@popjs/util.svg?branch=master)](https://travis-ci.org/imvkmark/popjs-util)
[![NPM downloads](http://img.shields.io/npm/dm/@popjs/util.svg?style=flat-square)](http://www.npmtrends.com/@popjs/util)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/imvkmark/popjs-util.svg)](http://isitmaintained.com/project/imvkmark/popjs-util "Percentage of issues still open")

Poppy Framework Js Util Packages

文档 : [中文文档](https://imvkmark.github.io/popjs-util/index.html)

## 使用者指南

通过npm下载安装代码

```bash
$ npm install --save @popjs/util
```

如果你是node环境

```js
var poppyjs = require('@popjs/util');
```

如果你是webpack等环境

```js
import { isMobile } from '@popjs/util';
```

如果你是requirejs环境

```js
requirejs(['node_modules/@popjs/util/dist/index.aio.js'], function(base) {
    // xxx
})
```

如果你是浏览器环境

```html

<script src="node_modules/@popjs/util/dist/index.aio.js"></script>
```

## 包的发布

发布之前需要生成 ts 文件

```
yarn doc
```

```
nrm use npm
yarn publish
```