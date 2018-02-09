# \<yo-image\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/michael-silva/yo-image)

A material file uploader with drag and drop

## Example of usage ##
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="yo-image.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<style>
    #result1 {
        display: block;
        width: 250px;
        height: 350px;
        margin: auto;
    }
</style>
<img id="result1" src="http://via.placeholder.com/250x350">
<yo-image target="#result1">
    <button confirm-crop>Confirm crop</button>
    <button cancel-crop>Cancel</button>
</yo-image>
```

## For developers ##

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

### Viewing Your Element

```
$ polymer serve
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
