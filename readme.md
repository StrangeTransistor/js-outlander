# js-outlander
## install
```sh
$ cd
$ npm i StrangeTransistor/js-outlander
```

## eslint
```sh
$ eslint -c ~/node_modules/js-outlander/outlander.eslint.js src/

# +Flow
$ eslint -c ~/node_modules/js-outlander/outlander-flow.eslint.js src/
```

`.eslintrc.js`
```js
module.exports =
{
	extends: require.resolve('js-outlander'),

	// +Flow
	extends: require.resolve('js-outlander/outlander-flow.eslint'),
}
```

## license
ISC © 2018 Strider.
