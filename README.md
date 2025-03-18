# sxiv.yazi






https://github.com/user-attachments/assets/e7679044-0188-4930-9298-a3fa454ee341






Preview and select image files through [sxiv-maomao](https://github.com/DreamMaoMao/sxiv)


## install
```bash
git clone https://github.com/DreamMaoMao/sxiv.yazi.git ~/.config/yazi/plugins/sxiv.yazi
``

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
