# zsh-editor

Customizable editor module for ZSH.

## Available options

The following options allow you to customize the editor module behaviour:

* `indicator`:

  * Description:

    Show an indicator while completing.

    _Note: If the indicator is enabled, then this plugin is incompatible with
    [zsh-autosuggestions](https://github.com/tarruda/zsh-autosuggestions)._

  * Usage:

    * Enable: `zstyle ':editor' indicator 'yes'`
    * Disable (default): `zstyle ':editor' indicator 'no'`

* `dot-expansion`:

  * Description:

    Automatically convert multiple dot sequences (e.g. `....` to `../..`).

  * Usage:

    * Enable: `zstyle ':editor' dot-expansion 'yes'`
    * Disable (default): `zstyle ':editor' dot-expansion 'no'`

* `key-bindings`:

  * Description:

    Set keybindings to a particular flavour.

  * Usage:

    * Vim-style: `zstyle ':editor' key-bindings 'vi'`
    * Emacs-style: `zstyle ':editor' key-bindings 'emacs'`

_Note: You should set these options **before** sourcing the module._

## License

Licensed under `Apache License 2.0`. More details [here](./LICENSE).
