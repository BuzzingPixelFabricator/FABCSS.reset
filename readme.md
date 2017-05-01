# Fabricator CSS/Less Reset

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

## Installing

With Fabricator and NPM, simply require this library into your project and restart the Fabricator Grunt build process.

`npm install fabcss.reset --save`

If you are not using Fabricator, you will need to include into your Less build `src/FABCSS.reset.les`.

## Usage

Variables available in this file you can override:

```
@bodyBackground: #fff;
@baseColor: lighten(#000, 25%);
@baseFont: Arial, Helvetica, sans-serif;
@baseFontSize: 16px;
@baseFontWeight: normal;
@baseLineHeight: 1em;
```
