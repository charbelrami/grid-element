# Grid Element

## Contents

- [Introduction](#introduction)
- [Installation](#installation)
  - [Bower](#bower)
  - [npm](#npm)
- [Usage](#usage)
  - [index.html](#indexhtml)
  - [Running locally](#running-locally)
- [Reference](#reference)
  - [grid-element](#grid-element-1)
    - [CSS Custom Properties](#css-custom-properties)
    - [Attributes](#attributes)
      - [Gutters](#gutters)
      - [Children alignment](#children-alignment)
  - [grid-col](#grid-col)
    - [Attributes](#attributes-1)
      - [Column sizing](#column-sizing)
      - [Individual alignment](#individual-alignment)
- [Browser support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Responsive grid element using Polymer and Flexbox

## Installation

### Bower

```
$ bower install grid-element
```

### npm

```
$ npm install grid-element
```

## Usage

### index.html

```html
<!doctype html>
<html>
  <head>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="bower_components/grid-element/grid-element.html">
  </head>
  <body>
    <grid-element>
      <grid-col></grid-col>
      <grid-col></grid-col>
      <grid-col></grid-col>
    </grid-element>
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

### grid-element

```html
<grid-element></grid-element>
```
#### CSS Custom Properties

- `--grid-gutter`: gutter size [default value: `10px`]
```css
--grid-gutter: 15px;
```

#### Attributes

##### Gutters

- `gs`: gutter size [type: `String`, initial value: `--grid-gutter` value]
```html
<grid-element gs="15px"></grid-element>
```
- `ghi`: inner horizontal gutters
```html
<grid-element ghi></grid-element>
```
- `gho`: outer horizontal gutters
```html
<grid-element gho></grid-element>
```
- `gvi`: inner vertical gutters
```html
<grid-element gvi></grid-element>
```
- `gvo`: outer vertical gutters
```html
<grid-element gvo></grid-element>
```

##### Children alignment

- `center`
```html
<grid-element center></grid-element>
```
- `start`
```html
<grid-element start></grid-element>
```
- `end`
```html
<grid-element end></grid-element>
```

### grid-col

```html
<grid-col></grid-col>
```

#### Attributes

##### Column sizing

- `s`: column stretching factor [type: `Number` - default value: `1`]
```html
<grid-col s="3"></grid-col>
```

##### Individual alignment

- `center`
```html
<grid-col center></grid-col>
```
- `start`
```html
<grid-col start></grid-col>
```
- `end`
```html
<grid-col end></grid-col>
```
- `stretch`
```html
<grid-col stretch></grid-col>
```

## Browser support

- [webcomponents.js](https://github.com/webcomponents/webcomponentsjs#browser-support)
- [Flexbox](http://caniuse.com/#feat=flexbox)

## Contributing

[Contributing](contributing.md)

## License

© 2015 Charbel Rami

[MIT](license.txt)
