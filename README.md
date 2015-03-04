# Spacing

The `spacing` module is a small collection of helper classes for spacings like
margin and padding.

## Dependencies

The Link-clean object depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)

If you install the `Responsive` module using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and `@import` these dependencies in the relevant way.

## Installation

You can install `Responsive` module via Bower, npm, Git Submodule, or copy and
paste.

### Install using Bower:

```sh
$ bower install tree-spacing --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-spacing/trump.spacing";
```

### Install using npm:

```sh
$ npm install tree-spacing --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/trump.spacing.git
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "trump.spacing/trump.spacing";

### Install via file download

The least recommended option for installation is to simply download
`_trump.spacing.scss` into your project and `@import` it into your
project in its Trump layer.

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
