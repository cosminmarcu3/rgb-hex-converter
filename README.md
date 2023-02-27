# rgb-hex-converter

Convert rgb to hex or/and hex to rgb

## install

$ npm i @colorconverters/rgb-hex-converter

## usage

import {rgbToHex} from "@colorconverters/rgb-hex-converter";

console.log(rgbToHex(255, 255, 34));

// Output:
// #ffff22

console.log(hexToRgb("#ffff22"));

// Output:
// [255, 255, 34]
