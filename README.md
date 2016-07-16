<img src="http://rawgit.com/caiogondim/hide-virtual-keyboard.js/master/img/icon.svg">

# hide-virtual-keyboard.js

Hides the virtual keyboard on a mobile device (iOS, Android, ...)

## Installation

### Bundler

To use the library, install it through [npm](https://npmjs.com)

```shell
npm install hide-virtual-keyboard
```

To port it to Browser or any other (non CJS) environment, use your favorite CJS
bundler. No favorite yet? Try: [Browserify](http://browserify.org/),
[Webmake](https://github.com/medikoo/modules-webmake) or
[Webpack](http://webpack.github.io/)

### Drop-in

If using a bunlder is not your thing, there is a file with UMD (Universal Module
Definition) under `dist/` folder. Just reference it on your browser (drop it)
and use it.

```html
<script src="dist/hide-virtual-keyboard.js"></script>
<script>
  setTimeout(_ => {
    window.hideVirtualKeyboard()
  }, 250)
</script>
```

## Usage

The module is a function that once called will blur from current focused input,
hiding the virtual keyboard.

```js
hideVirtualKeyboard()
```
