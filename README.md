# &lt;enlighted-link&gt;

> A bare minimum custom element starter-kit using [VanillaJS](http://vanilla-js.com/).
>
> Looking for a working example? Check [hello-world-element](https://github.com/webcomponents/hello-world-element).

## Demo

[Check it live!](http://Juicy.github.io/enlighted-link)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install enlighted-link --save
```

Or [download as ZIP](https://github.com/Juicy/enlighted-link/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponent-lite.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/enlighted-link/enlighted-link.html">
    ```

3. Start using it!

    ```html
    <enlighted-link></enlighted-link>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## CSS Custom Properties

Name                          | Description
---                           | ---
`--enlighted-link-laser-color` | Color of the shooted lasers.

## [Contributing and Development](CONTRIBUTING.md)

## History

For detailed changelog, check [Releases](https://github.com/Juicy/enlighted-link/releases).

## License

MIT
