# Deep Blue See

> A Sublime Text Color Scheme.

Supports the usual plus:

* [GitGutter](https://github.com/jisaacks/GitGutter)
* [ASCIIPresentation](https://github.com/chrisbreiding/ASCIIPresentation)

### Contributing

Install the node packages

```shell
$ npm install
```

Edit the `scheme.coffee` file to make changes to the color scheme.

To compile to `.tmTheme` run:

```shell
$ coffee compiler.coffee > "Deep Blue See.tmTheme"
```

Optionally you can run:

```shell
coffee watch.coffee
```

To have the theme automatically compile as you make changes.