# Distribution Bar Web Component \<alump-dbar\>

[![Build Status](https://travis-ci.org/alump/alump-dbar.svg?branch=master)](https://travis-ci.org/alump/alump-dbar)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/alump/alump-dbar)
[![GitHub tag](https://img.shields.io/github/tag/alump/alump-dbar.svg?style=plastic)](https://github.com/alump/alump-dbar/releases)
[![Bower](https://img.shields.io/bower/v/alump-dbar.svg?style=plastic)](https://bower.io/)
[![GitHub issues](https://img.shields.io/github/issues/alump/alump-dbar.svg?style=plastic)](https://github.com/alump/alump-dbar/issues)

[Online demo at webcomponents.org](https://www.webcomponents.org/element/alump/alump-dbar/demo/demo/index.html)

## Examples

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="alump-dbar.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<alump-dbar values="[34,66]" class="alump-shade alump-r20" style="width: 100%;">
</alump-dbar>
```

## Releases
### 0.1.2 (2017-08-07)
* aria-label and aria-valuenow attributes are now generated for items
* Item formatted can now return number, string or object (with 'text' and 'html' values). Object to be used when HTML coding is used.
* Color of items can be now be defined in itemFormatter (will override theming colors when defined)
* Using now background CSS property on items, to allow gradients and images
* Fix naming of valuesum to valueSum
* --alump-dbar-font-size and --alump-dbar-font-family custom styling properties added
* Fix --alump-dbar-text-shadow to always apply when defined
* Make update (schedule render) function public, usually there should not be need to call this
### 0.1.1 (2017-08-04)
* Fixing project metadata to improve presentation at webcomponents.org
* Fix overdrawn content, adding --alump-dbar-padding variable
### 0.1.0 (2017-08-04)
* Initial release

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
