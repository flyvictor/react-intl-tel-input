# Vic-React-Intl-Tel-Input
This is a fork of https://github.com/patw0929/reactintl-tel-input.


## Collaborators Wanted!

Due to the long commuting time, I have no much time to maintain this project often. 😣

So If anybody else is willing to take on the work of bug fixes, integrating pull requests, etc.
Please let me know. 🙌

I hope we can maintain the project together, and make this project better! 💪

## Demo & Examples

To build the examples locally, run:

```bash
npm install
npm start
```

or

```bash
yarn
yarn start
```

Then open [`localhost:3000`](http://localhost:3000) in a browser.


## Installation

The easiest way to use react-intl-tel-input is to install it from NPM and include it in your own React build process (using [Webpack](http://webpack.github.io/), etc).

You can also use the standalone build by including `dist/main.js` in your page. If you use this, make sure you have already included React, and it is available as a global variable.

```bash
npm install react-intl-tel-input --save
```

or

```bash
yarn add react-intl-tel-input
```


## Usage

```javascript
import IntlTelInput from 'react-intl-tel-input';
import 'react-intl-tel-input/dist/main.css';

<IntlTelInput
  containerClassName="intl-tel-input"
  inputClassName="form-control"
/>
```

## Development (`src` and the build process)

**NOTE:** The source code for the component is in `src`. A UMD bundle is also built to `dist`, which can be included without the need for any build system.

To build, watch and serve the examples (which will also watch the component source), run `npm start`.

If you want to build to the bundle file to `dist/` folder, please run:

```bash
npm run build
```

or

```bash
yarn run build
```

## Contributing

To contribute to react-intl-tel-input, clone this repo locally and commit your code on a separate branch. Please write tests for your code, and run the linter before opening a pull-request:

```bash
npm test
npm run lint
```

or

```bash
yarn test
yarn run lint
```

## Inspired by

[International Telephone Input](https://github.com/patw0929/react-intl-tel-input)


## License

MIT

Copyright (c) 2015-2019.

