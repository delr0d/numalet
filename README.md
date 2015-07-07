# numalet [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]
> Convierte número decimal a letra


## Instalación

```sh
$ npm install --save numalet
```


## Uso

```js
#Unidades por defecto 'MXN', texto en mayúsculas
var num2Let = require('numalet')();

#Unidades 'M.N' y texto en minúsculas
var num2Let = require('numalet')({unidad:'M.N',mayus:false});

num2Let(1743.43);
# MIL SETECIENTOS CUARENTA Y TRES 43/100 MXN

num2Let(9473211.34);
#NUEVE MILLONES CUANTROCIENTOS SETENTA Y TRES MIL DOSCIENTOS ONCE 34/100 MXN
```

## Licencia

MIT © [Rubén Rivera Lomelí]()


[npm-image]: https://badge.fury.io/js/numalet.svg
[npm-url]: https://npmjs.org/package/numalet
[travis-image]: https://travis-ci.org//numalet.svg?branch=master
[travis-url]: https://travis-ci.org//numalet
[daviddm-image]: https://david-dm.org//numalet.svg?theme=shields.io
[daviddm-url]: https://david-dm.org//numalet
[coveralls-image]: https://coveralls.io/repos//numalet/badge.svg
[coveralls-url]: https://coveralls.io/r//numalet
