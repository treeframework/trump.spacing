# Spacing

The `spacing` module is a small collection of helper classes for spacings like
margin and padding.

## Dependencies

The `spacing` module depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)

If you install the `spacing` module using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and `@import` these dependencies in the relevant way.

## Installation

You can install `spacing` module via Bower, npm, Git Submodule, or copy and
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
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.spacing.scss` into your project and `@import` it into your
project in its Trump layer.

## Usage

The classes take the following form: `.u-[negative][type][direction][size]`

### Negative

`-`

### Types

`m` &mdash; margin

`p` &mdash; padding

### Direction

`t` &mdash; top

`r` &mdash; right

`b` &mdash; bottom

`l` &mdash; left

`h` &mdash; horizontal

`v` &mdash; vertical

### Sizes

`0` &mdash; none

`--` &mdash; tiny

`-` &mdash; small

`+` &mdash; large

`++` &mdash; huge

### Example

```html
<blockquote>
    <p class="u-mb0">Margin bottom none</p>
</blockquote>
```

```html
<header class="u-mb+">
    Margin bottom large
</header>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
