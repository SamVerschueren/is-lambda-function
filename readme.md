# is-lambda-function [![Build Status](https://travis-ci.org/SamVerschueren/is-lambda-function.svg?branch=master)](https://travis-ci.org/SamVerschueren/is-lambda-function)

> Detect if your code is running in [AWS Lambda](https://aws.amazon.com/lambda/)


## Install

```
$ npm install --save is-lambda-function
```


## Usage

```js
const isLambdaFunction = require('is-lambda-function');

if (isLambdaFunction) {
	console.log('Running in AWS Lambda');
}
```


## License

MIT © [Sam Verschueren](https://github.com/SamVerschueren)
