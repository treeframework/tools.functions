# Functions

The `functions` module is **required** for using any of the rest of the
framework.

## Installation

You can install the `functions` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-functions --save
```

Once installed, `@import` into your project in its Tools layer:

```scss
@import "bower_components/tree-functions/tools.functions";
```

### Install using npm:

```sh
$ npm install tree-functions --save
```

### Install via file download

The least recommended option for installation is to simply download 
`_tools.functions.scss` into your project and `@import` it into your  project in
its Tools layer.

## Usage

Basic usage of the `functions` module:

```scss
.foo {
    padding: halve(10px);
}
```

This will yield:

```css
.foo {
    padding: 5px;
 }
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
