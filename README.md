# nvim-dots

Personal Neovim config files, fork of [Kickstart.nvim](https://docs.github.com/en/get-started/quickstart/fork-a-repo](https://github.com/nvim-lua/kickstart.nvim ) 

# Installation

### Dependencies

External Requirements:
- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- LSP Dependencies: `python`, `npm`, `nodejs`, `go`
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation),
  [fd-find](https://github.com/sharkdp/fd#installation)
- Clipboard tool (xclip/xsel/win32yank or other depending on the platform)
- A [Nerd Font](https://www.nerdfonts.com/)

### How to install

Clone this repo in your Nvim dotfiles:

```sh
git clone https://github.com/ajsandovalt/nvim-dots.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
Start Nvim to trigger the installation.
