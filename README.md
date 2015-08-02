# svg-modify
This fork is special version for my fork of grunt-svg-modify. 

Modify SVG by JSON.

> ________________________

Svg-modify helps you to resize SVG-images, colorize them and make a number of variations of one file.

It may be useful if you need to prepare SVG images for convertation to PNG.

## Getting Started

```shell
npm install svg-modify --save-dev
```

## Release History

0.0.10 — Add global colorize option. Use `svgmodify.colorize = false;` to switch colorize off.

0.0.9 - Add cleaning of SVG content. Comments, title, desc, Sketch attributes and ID will be removed from symbols.

0.0.8 - Fix modifications created with hex colors

0.0.6 - Add ability to use `colorize: false` if images needn't be colorized though colors in config are exist

0.0.5 - Now fill color correctly overrides with color from config

0.0.4 - Add ability colorize without additional configs


