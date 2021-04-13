# My fork of [dmenu](https://tools.suckless.org/dmenu/) from suckless

## Requirements

In order to build dmenu you need the Xlib header files.

## Installation

```sh
make
sudo make install
```

## Running dmenu

To run dmenu, run:

```sh
dmenu_run [options]
```

## Options

| Option | Description                                         | Value type |
| ------ | --------------------------------------------------- | ---------- |
| b      | appears on the bottom                               | None       |
| f      | grabs the keyboard befre reading stdin              | None       |
| s      | matches menu items case sensitively                 | None       |
| n      | instantly selects if only one match                 | None       |
| l      | long listing format                                 | Int        |
| h      | uses a menu line of at least 'height' pixels tall   | Int        |
| m      | select which monitor dmenu appears on (starts at 0) | Int        |
| p      | prompt name                                         | Str        |
| fn     | font used                                           | Str        |
| nb     | normal background color                             | Str        |
| nf     | normal foreground color                             | Str        |
| sb     | selected background color                           | Str        |
| sf     | selected foreground color                           | Str        |
| v      | prints version number                               | None       |
| w      | embed into windowid                                 | Int        |
