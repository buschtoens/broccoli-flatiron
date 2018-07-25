# Broccoli Flatiron

## Usage

Create a payload file based upon directory structure.

```javascript
var flatiron = require("broccoli-flatiron");

var options = {
    outputFile: 'path/to/output/file'
};

var tree = flatiron(targetDirectory, options);
```

## Documentation

- `option.outputFile` - path of the generated file
- `option.trimExtensions` - trim file extensions object keys or not
- `option.prefix` - use custom prefix, `default: export default`
- `option.suffix` - use custom suffix, `default: ;`

## ZOMG!!! TESTS?!?!!?

Yeah, I know.

```javascript
npm install
npm test
```

## License

This project is distributed under the MIT license.
