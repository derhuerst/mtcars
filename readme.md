# mtcars

**A testing dataset containing car measurements.** Also, checkout the [CSV version](https://gist.github.com/seankross/a412dfbd88b3db70b74b).

> *mtcars* is a demonstration dataset included in every R installation. It is a 32 x 11 data.frame: 11 measures (horsepower, engine displacement, miles per gallon, ...) on 32 cars published in the 1974 Motor Trend magazine. Of limited intrinsic interest, it is nonetheless useful for learning introductory data exploration techniques.

– [*Explore a classic R dataset: mtcars*](https://github.com/oncoscape/chinook/wiki/Explore--a-classic-R-dataset:--mtcars)

[![npm version](https://img.shields.io/npm/v/mtcars.svg)](https://www.npmjs.com/package/mtcars)
![ISC-licensed](https://img.shields.io/github/license/derhuerst/mtcars.svg)
[![chat on gitter](https://badges.gitter.im/derhuerst.svg)](https://gitter.im/derhuerst)


## Installing

```shell
npm install mtcars
```


## Usage

```js
const mtcars = require('mtcars')

console.log(mtcars[0])
```

```js
{
	model: 'Mazda RX4',
	mpg: 21,
	cyl: 6,
	disp: 160,
	hp: 110,
	drat: 3.9,
	wt: 2.62,
	qsec: 16.46,
	vs: 0,
	am: 1,
	gear: 4,
	carb: 4
}
```


## Source

[Henderson and Velleman (1981), Building multiple regression models interactively. Biometrics, 37, 391–411.](http://hsta559s12.pbworks.com/w/file/fetch/52612745/mtcars.pdf)
