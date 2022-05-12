# Fish lf Icons

![fish lf icons screenshot](./fish-lf-icons-screenshot.jpg)

A [fish](https://fishshell.com) plugin that adds Nerd Font icons to the [lf](https://github.com/gokcehan/lf) terminal file manager

## Prerequisites

You must have the following binaries already installed on your machine:

- [fish](https://fishshell.com) shell
- [fisher](https://github.com/jorgebucaran/fisher) package manager
- [lf](https://github.com/gokcehan/lf) terminal file manager

## How to install

Run the following command to install the plugin:

```fish
fisher install joshmedeski/fish-lf-icons
```

Then, make sure to **enable icons in lf** by adding the following line to your `~/.config/lf/lfrc` config file.

```
set icons
```

## How to update

To update this plugin, run the following command:

```fish
fisher update joshmedeski/fish-lf-icons
```

## How to remove / uninstall

To uninstall this package, remove the line from the "How to install" section and run the following command

```fish
fisher uninstall joshmedeski/fish-lf-icons
```

## How to contribute

To contribute, simply fork and clone this repo, make the changes you want, then open a pull request!

## Alternative plugin managers

[fisher](https://github.com/jorgebucaran/fisher) and [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) are also supported. However, I prefer fisher. See [How does Fisher compare to Oh My Fish and Fundle?](https://github.com/jorgebucaran/fisher/issues/481) for more.

## Thanks

- [lf](https://github.com/gokcehan/lf) for being an amazing tool! Icon support is just icing on the cake 🍰
- [Nerd Font](https://www.nerdfonts.com) for making the terminal cooler 😎
- [fisher](https://github.com/jorgebucaran/fisher) for making it easy to create a fish plugin and share it wit the world 🌐
- [lsd](https://github.com/Peltoche/lsd) for great Nerd Font support that helped make this plugin better.
