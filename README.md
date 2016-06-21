# https://github.com/domenic/svg2png/issues/49

The upgrade to 3.0.0 is causing the output png to have a tonne of whitespace.

dest-2.1.0.png is source.svg after being ran through svg2png@2.1.0, while
dest-3.0.0.png is source.svg after being ran through svg2png@3.0.0. They're
pretty different!

To run the script, `npm install` and then `node .`.
