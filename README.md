# inuitcss-base.vewport

Bulletproof viewport for [Inuitcss](http://www.inuitcss.com)

`<meta>` element is a strange place to specify the viewport. But it work ... now. But will it work in the futur ?

[W3C standard approach to specify viewport style information](http://dev.w3.org/csswg/css-device-adapt/ "CSS Device Adaptation Module Level 1").

## Viewport map

Define a custom `$inuit-viewport` variable like that:

```scss
$inuit-viewport: (
  width: device-width,
  initial-scale: 1,
  ...
  );
```

## Install

```
$ bower install --save inuit-viewport
```
