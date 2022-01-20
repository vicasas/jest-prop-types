# jest-prop-types

This little library improves support for accessory types in Jest by failing accessory type bug tests instead of ignoring them.

Every time the test runs and every time a faulty accessory is sent to your component, the accessory type validation will detect it and cause the test to fail.

## Installation

```sh
npm install --save-dev jest-prop-types
```

## Usage

To catch accessory errors and Jest fail the test, you need to add the following to your `jest.config.js` file.

```js
{
  "setupFiles": [
    "jest-prop-types"
  ]
}
```

### Whit Create React App

[Create React App](https://create-react-app.dev/) does not allow the use of `setupFiles`, instead add `jest-prop-types` to your `setupTests.js` file.

```js
import 'jest-prop-types'
```

## Contributing

Read the [contributing guide](/CONTRIBUTING.md) to learn about our development process, how to propose bugfixes and improvements.

## Changelog

To see what has changed visit our [CHANGELOG.md](/CHANGELOG.md).

## License

This project is licensed under the terms of the [MIT license](/LICENSE).
