# StreamDeck


To learn the commands needed to open your app,
execute the followin command,
then PRESS inside the window of interest.

```shell
 $ xprop | grep 'CLASS'
```

### Nautilius (file browser) use: nautilius
```shell
WM_CLASS(STRING) = "org.gnome.Nautilus", "Org.gnome.Nautilus"
```

### VS Code - use: code
```shell
WM_CLASS(STRING) = "code", "Code"
```

### Settings (previously visited)
```shell
WM_CLASS(STRING) = "gnome-control-center", "Gnome-control-center"
```

### Obsidian (notes) - use obsidian
```shell
WM_CLASS(STRING) = "obsidian", "obsidian"
```

### Terminal - use: gnome-terminal (opens a new one)
```shell
WM_CLASS(STRING) = "gnome-terminal-server", "Gnome-terminal"
```

### Stream Deck app - nothing works
```shell
WM_CLASS(STRING) = "streamdeck", "Streamdeck UI"
```


