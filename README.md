# nvim-dots

Personal Neovim config files, fork of [Kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) 

# Installation

### Dependencies

External Requirements:
- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation),
  [fd-find](https://github.com/sharkdp/fd#installation)
- [tree-sitter CLI](https://github.com/tree-sitter/tree-sitter/blob/master/crates/cli/README.md#installation)
- LSP Dependencies: `python`, `npm`, `nodejs`, `go`
- Clipboard tool (xclip/xsel/win32yank or other depending on the platform)
- A [Nerd Font](https://www.nerdfonts.com/)

### How to install

Clone this repo in your Neovim dotfiles:

```sh
git clone https://github.com/ajsandovalt/nvim-dots.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
Start Neovim to trigger the installation.
