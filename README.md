# smart-enter.yazi

This is a Yazi plugin for a smart enter key.

## Installation

Install the plugin:

```
ya pkg add Ape/smart-enter
```

Create `~/.config/yazi/keymap.toml` and add:

```
[[mgr.prepend_keymap]]
on   = "<Enter>"
run  = "plugin smart-enter"
desc = "Enter the child directory, or open the file"
```

## Acknowledgements

The plugin was originally adopted from the Tips page in Yazi docs.
