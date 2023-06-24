# pyvipe

* [INTRODUCTION](#introduction)
* [INSTALLATION](#installation)
    * [PIP](#pip)
    * [MANUAL_INSTALLATION](#manual-installation)
* [USAGE](#usage)
* [ENVIRONMENT_VARIABLES](#environment-variables)
* [CONTRIBUTION](#contribution)

## INTRODUCTION

**pyvipe** is a Python port of [vipe](http://joeyh.name/code/moreutils/).

This project is a by-product of [trrc](https://github.com/Constantin1489/trrc) feature development.

## INSTALLATION

### pip

`pip install pyvipe`

### Manual Installation

`pip install .`

## USAGE

```
command1 | vipe | command2
```

Use `--suffix` to apply file syntax highlighting.

## Environment Variables

**pyvipe** chooses the editor to use via looking for editors which are `/usr/bin/editor`, `$EDITOR`, `$VISUAL`, in order.

## CONTRIBUTION

If it doesn't work as original [vipe](http://joeyh.name/code/moreutils/), then it's a bug.

## Thanks to

[Nick ODell](https://stackoverflow.com/a/76527291/20307768)
