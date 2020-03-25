# jshint-stylishexitonerror

## Install

```
$ npm install --save-dev jshint-stylishexitonerror
```

## Usage

```js
gulp.task('default', () =>
	gulp.src(['file.js'])
		.pipe(jshint())
		.pipe(jshint.reporter('jshint-stylishexitonerror'))
);
```