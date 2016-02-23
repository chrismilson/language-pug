# language-pug package

A [Pug](https://github.com/pugjs) (was **Jade**) syntax highlighting for Atom, derived from [jade-tmbundle](https://github.com/davidrios/jade-tmbundle).

### Development

This syntax is meant to be maintained and fixed in all his known bugs, it is used by the [Objectway](https://github.com/Objectway) front end team.

### Collaborate

Any improvement, suggestion, bugfix is really appreciated.

### Bugs

One pesky bug is the one involving comments that are not rendered properly:

[FirstMate issue 38](https://github.com/atom/first-mate/issues/38)

Any help in fixing this one is more than welcome!

### Install

`$ apm install language-pug`


### Configure

In your `config.cson` write:

```
".pug.text":
  whitespace:
    removeTrailingWhitespace: false
```

### License

This package is published under MIT license
