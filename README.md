[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/monkick/scatter-menu)

# \<scatter-menu\>

This is menu.

## Version
1.0

## DEMO

Look at page of demo

## Installation

```
$ bower install --save monkick/scatter-menu
```

## Usage

At first. Import it at header.

```html
    <link rel="import" href="../bower_components/scatter-menu/scatter-menu.html">
    <link rel="import" href="../bower_components/scatter-menu/scatter-menu-item.html">
```

Next. Add the `scatter-menu` custom tag and put some `scatter-menu-item` in `scatter-menu`.

```html
    <scatter-menu row="3" col="3">
        <scatter-menu-item menu-title="menu01" menu-order="1" menu-space="80"></scatter-menu-item>
        <scatter-menu-item menu-title="menu02" menu-order="2" menu-space="80"></scatter-menu-item>
        <scatter-menu-item menu-title="menu03" menu-order="3" menu-space="80"></scatter-menu-item>
        <scatter-menu-item menu-title="menu04" menu-order="1" menu-space="80" menu-column="2"></scatter-menu-item>
        <scatter-menu-item menu-title="menu05" menu-order="2" menu-space="80" menu-column="2"></scatter-menu-item>
        <scatter-menu-item menu-title="menu06" menu-order="3" menu-space="80" menu-column="2"></scatter-menu-item>
        <scatter-menu-item menu-title="menu07" menu-order="1" menu-space="80" menu-column="3"></scatter-menu-item>
        <scatter-menu-item menu-title="menu08" menu-order="2" menu-space="80" menu-column="3"></scatter-menu-item>
        <scatter-menu-item menu-title="menu09" menu-order="3" menu-space="80" menu-column="3"></scatter-menu-item>
    </scatter-menu>
```

### <scatter-menu>

* row: Row number of menu.
* col: Column number of menu.

### <scatter-menu-item>

* menu-title: Title of menu.
* menu-order: Order of menu in row.
* menu-space: Space of menu.
* menu-column: Column of menu.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
