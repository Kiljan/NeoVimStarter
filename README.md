# For me, one of the best ways to configure Neovim with [NvChad](https://nvchad.com/) 

### Original project can be found at https://github.com/NvChad/NvChad

## Pre-requisites

- Neovim 0.9.5.
- Nerd Font as your terminal font.
- GCC
- make

### Delete old neovim folders (check commands below)

## Install

```bash
git clone https://github.com/Kiljan/NeoVimStarter ~/.config/nvim && nvim
# Run :MasonInstallAll command after lazy.nvim finishes downloading plugins.
```

## Uninstall

### Linux / Macos (unix)
rm -rf ~/.config/nvim
rm -rf ~/.local/share/nvim

## Additional info

- After lazy download plugin "pyright" I add to ".config/nvim/init.lua" python LSP

  ```lua
  -- for Python lsp
      require'lspconfig'.pyright.setup{}
  ```
- There are many plugins and You can adapt everything for Your needs
