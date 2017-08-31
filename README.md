# createjs
⛩  Install createJS by npm

## Libs
 - [easeljs-0.8.2.combined.js](https://github.com/CreateJS/EaselJS)
 - [preloadjs-0.6.2.combined.js](https://github.com/CreateJS/PreloadJS)
 - [soundjs-0.6.2.combined.js](https://github.com/CreateJS/SoundJS)
 - [tweenjs-0.6.2.combined.js](https://github.com/CreateJS/TweenJS)

## Install
```bash
$ yarn add yuki-createjs
# or
$ npm install yuki-createjs --save
```

## Usage

### Include all
```js
import 'createjs'
// or
require('createjs')

// then
console.log(createjs) // <- Global 🍻
```

### Just one
```js
import 'createjs/lib/preloadjs-0.6.2.combined'
// or
require('createjs/lib/preloadjs-0.6.2.combined')

// then 🍻
var preload = new createjs.LoadQueue()
```
