# zsh-editor

Customizable editor module for ZSH.

## Available options

The following options allow you to customize the editor module behaviour.

*Note: You should set these options **before** sourcing the module.*

* `export-key-info`:

  Description:

  Export an environment variable called `KEY_INFO` which contains *mnemonic*
  key-info for some commonly used keys (like Control, etc..).

  Usage:

  * Enable: `zstyle ':editor' export-key-info 'yes'`
  * Disable (default): `zstyle ':editor' export-key-info 'no'`

* `dot-expansion`:

  Description:

  Automatically convert multiple dot sequences (e.g. `....` to `../..`).

  Usage:

  * Enable: `zstyle ':editor' dot-expansion 'yes'`
  * Disable (default): `zstyle ':editor' dot-expansion 'no'`

* `key-bindings`:

  Description:

  Set keybindings to a particular flavour.

  Usage:

  * Vim-style: `zstyle ':editor' key-bindings 'vi'`
  * Emacs-style: `zstyle ':editor' key-bindings 'emacs'`

- `:editor`
