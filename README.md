# Furtive Media Object

A simple, extensible media object using `display: flex;`. Used in [furtive.css](http://furtive.co).

<http://caniuse.com/#search=flex>

## Installation

It's recommended to use [rework-npm](https://github.com/reworkcss/rework-npm):

```
npm install --save furtive-media-object
```

```javascript
var rework = require('rework'),
    reworkNPM = require('rework-npm');

var output = rework('@import "furtive-media-object";', { source: 'my-file.css' })
    .use(reworkNPM());
```

Or, through npm the old-fashioned way:

```
npm install --save furtive-media-object
```

## Usage

Detailed documentation and examples can be found at [furtive.co](http://furtive.co).

## Acknowledgements

Adapted from <http://philipwalton.github.io/solved-by-flexbox/demos/media-object/>

## License

MIT

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by [John Otander](http://johnotander.com) ([@4lpine](https://twitter.com/4lpine)).
