# Flex Element

## Contents

- [Introduction](#introduction)
- [Installation](#installation)
  - [Bower](#bower)
  - [npm](#npm)
- [Usage](#usage)
  - [index.html](#indexhtml)
  - [Running locally](#running-locally)
- [Reference](#reference)
  - [flex-element](#flex-element-1)
    - [Attributes](#attributes)
      - [Children alignment](#children-alignment)
        - [x-axis](#x-axis)
        - [y-axis](#y-axis)
- [Browser support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Flexbox element

## Installation

### Bower

```
$ bower install flex-element
```

### npm

```
$ npm install flex-element
```

## Usage

### index.html

```html
<!doctype html>
<html>
  <head>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="bower_components/flex-element/flex-element.html">
  </head>
  <body>
    <flex-element>
    </flex-element>
  </body>
</html>
```

### Running locally

#### polyserve

```
$ npm install --global polyserve
```

```
$ polyserve
```

## Reference

### flex-element

```html
<flex-element></flex-element>
```

#### Attributes

##### Children alignment

###### x-axis

- `x-center`
```html
<flex-element x-center></flex-element>
```
- `x-start`
```html
<flex-element x-start></flex-element>
```
- `x-end`
```html
<flex-element x-end></flex-element>
```

- `x-space-around`
```html
<flex-element x-space-around></flex-element>
```

- `x-space-between`
```html
<flex-element x-space-between></flex-element>
```

###### y-axis

- `y-baseline`
```html
<flex-element y-baseline></flex-element>
```
- `y-center`
```html
<flex-element y-center></flex-element>
```
- `y-start`
```html
<flex-element y-start></flex-element>
```

- `y-end`
```html
<flex-element y-end></flex-element>
```

- `y-stretch`
```html
<flex-element y-stretch></flex-element>
```

## Browser support

- [webcomponents.js](https://github.com/webcomponents/webcomponentsjs#browser-support)
- [Flexbox](http://caniuse.com/#feat=flexbox)

## Contributing

[Contributing](contributing.md)

## License

© 2015 Charbel Rami

[MIT](license.txt)
