# open-kitty-here

Adds a service menu to KDE Dolphin (file manager) which allows you to open the [Kitty](https://github.com/kovidgoyal/kitty) terminal in the current directory.

## How to install

1\. Copy and paste this command in your terminal (KDE6) 👇

```zsh
mkdir -p ~/.local/share/kio/servicemenus \
	&& wget https://raw.githubusercontent.com/raphtlw/open-kitty-here/master/kittyhere.desktop \
	-O ~/.local/share/kio/servicemenus/kittyhere.desktop
```

2\. Restart Dolphin or run `kbuildsycoca6`

3\. Enjoy! 🚀

> KDE5 users: use `~/.local/share/kservices5/ServiceMenus/` and `kbuildsycoca5` instead.
