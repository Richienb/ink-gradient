# ink-gradient [![Build Status](https://travis-ci.com/sindresorhus/ink-gradient.svg?branch=master)](https://travis-ci.com/github/sindresorhus/ink-gradient)

> Gradient color component for [Ink](https://github.com/vadimdemedes/ink)

![](screenshot.png)

Looking for a version compatible with Ink 2.x? Check out [this release](https://github.com/sindresorhus/ink-gradient/tree/v1.0.0).

## Install

```
$ npm install ink-gradient
```

## Usage

```js
import React from 'react';
import {render} from 'ink';
import Gradient from 'ink-gradient';
import BigText from 'ink-big-text';

render(
	<Gradient name="rainbow">
		<BigText text="unicorns"/>
	</Gradient>
);
```

## API

### `<Gradient>`

It accepts a string or Ink component as `children`, for example, [`ink-box`](https://github.com/sindresorhus/ink-box).

#### Props

##### name

Type: `string`

Name of a [built-in gradient](https://github.com/bokub/gradient-string#available-built-in-gradients).

##### colors

Type: `string[] | object[]`

[Colors to use to make the gradient.](https://github.com/bokub/gradient-string#initialize-a-gradient)

## Related

- [ink-box](https://github.com/sindresorhus/ink-box) - Box component for Ink
- [ink-big-text](https://github.com/sindresorhus/ink-big-text) - Awesome text component for Ink
- [ink-link](https://github.com/sindresorhus/ink-link) - Link component for Ink
