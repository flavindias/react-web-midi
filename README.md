# React Web MIDI

This is a simple React MIDI component that allows you to drop in a <Midi /> component to interact with your Midi Controller, Mouse, or Keyboard.

This is a work in progress!


## Demo & Examples

Live demo: [erictherobot.github.io/react-web-midi](http://erictherobot.github.io/react-web-midi/)

To build the examples locally, run:

```
yarn
yarn start
```

Then open [`localhost:8000`](http://localhost:8000) in a browser.


## Installation

The easiest way to use react-web-midi is to install it from NPM and include it in your own React build process (using [Browserify](http://browserify.org), [Webpack](http://webpack.github.io/), etc).

You can also use the standalone build by including `dist/react-web-midi.js` in your page. If you use this, make sure you have already included React, and it is available as a global variable.

```
yarn add react-web-midi
```


## Usage

```
import ReactWebMidi from 'react-web-midi'

<ReactWebMidi />
```

### Properties

* There are no props yet. I'm still exploring the MIDI API. Check back soon.

### Notes

This project is inspired by the work of:
- Keith McMillen - https://www.keithmcmillen.com
- https://webaudio.github.io/web-midi-api
- https://github.com/cwilso/WebMIDIAPIShim

## Development (`src`, `lib` and the build process)

**NOTE:** The source code for the component is in `src`. A transpiled CommonJS version (generated with Babel) is available in `lib` for use with node.js, browserify and webpack. A UMD bundle is also built to `dist`, which can be included without the need for any build system.

To build, watch and serve the examples (which will also watch the component source), run `npm start`. If you just want to watch changes to `src` and rebuild `lib`, run `npm run watch` (this is useful if you are working with `npm link`).

## License

MIT License

Copyright (c) 2017 Eric David Smith.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
