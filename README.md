# sxiv.yazi





https://github.com/user-attachments/assets/68bdc875-5380-4a3b-91ad-86975472109a




Preview and select image files through [sxiv-maomao](https://github.com/DreamMaoMao/sxiv)


## Usage

Add this to your `~/.config/yazi/keymap.toml`:

```toml
[[manager.prepend_keymap]]
on   = ["c", "i"]
run  = "plugin sxiv"
desc = "Preview images in sxiv"
```

## action in sxiv-maomao
- move: h/j/k/l/up/down/right/left
- toggle-fullwindow: f
- select: space
- select or jump: return (if no select files will jump current)

```
```

## License

This plugin is MIT-licensed. For more information check the [LICENSE](LICENSE) file.
