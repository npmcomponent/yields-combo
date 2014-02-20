*This repository is a mirror of the [component](http://component.io) module [yields/combo](http://github.com/yields/combo). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-combo`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# combo

  Keyboard combo like Gmail.

## Installation

    $ component install yields/combo

## Example

```js
window.onkeyup = combo(['f', 'g'], 300, function(e){
  // the method will be invoked only if
  // `f` was pressed and then within `300ms`
  // `g` was pressed as well.
});
```

## API

#### combo(keys[, ms], fn)

`ms` is defaulted to `300`.

## License

  MIT
