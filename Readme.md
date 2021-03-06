*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-dot-case](http://github.com/ianstormtaylor/to-dot-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-dot-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-dot-case

  Convert a string to a dot case.

## Installation

    $ component install ianstormtaylor/to-dot-case
    $ npm install to-dot-case

## Example

```js
var dot = require('to-dot-case');

dot('camelCase');  // "camel.case"
dot('space case'); // "snake.case"
dot('slug-case');  // "slug.case"
dot('weird[case'); // "weird.case"
```

## API

### toDotCase(string)
  
  Returns the dot-case variant of a `string`.

## License

  MIT
