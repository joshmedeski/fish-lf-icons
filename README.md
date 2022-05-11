# Fish lf Icons

A [fish](https://fishshell.com) plugin that adds Nerd Font icons to the [lf](https://github.com/gokcehan/lf) terminal file manager

## Prerequisites

You must have the following binaries already installed on your machine:

- [fish shell](https://fishshell.com)
- [fundle package manager](https://github.com/danhper/fundle)
- [lf terminal file manager](https://github.com/gokcehan/lf)

## How to install

Add the following line to your fish config file (`~/.config/fish/config.fish`)

```fish
fundle plugin 'james2doyle/omf-plugin-fnm'
```

**Note:** this must go before `fundle init` (see [fundle](https://github.com/danhper/fundle) for more info)

## How to update

To update this plugin, run the following command

```fish
fundle update joshmedeski/fish-lf-icons
```

**Note:** you can run `fundle update` to update all your packages at once.

## How to remove / uninstall

To uninstall this package, remove the line from the "How to install" section and run the following command

```fish
fundle clean
```

## How to contribute

To contribute, simply fork and clone this repo, make the changes you want, then open a pull request!

## Thanks

- [lsd](https://github.com/Peltoche/lsd) has great Nerd Font file icon support
- [lf](https://github.com/gokcehan/lf) has some good examples of how to Nerd Font add icon support
