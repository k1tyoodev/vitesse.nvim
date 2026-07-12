# cursor.nvim

A minimal Neovim theme matching Ghostty's built-in Cursor Dark and Cursor Light palettes.

## Install

```lua
{
  "k1tyoodev/cursor.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme(vim.o.background == "light" and "cursor-light" or "cursor-dark")
  end,
}
```

## Options

```lua
require("cursor-dark").setup({ transparent = false })
require("cursor-light").setup({ transparent = false })
```

## Supported plugins

- [blink.cmp](https://github.com/Saghen/blink.cmp)
- [flash.nvim](https://github.com/folke/flash.nvim)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [mini.diff](https://github.com/nvim-mini/mini.diff)
- [mini.statusline](https://github.com/nvim-mini/mini.statusline)
- [oil.nvim](https://github.com/stevearc/oil.nvim)
- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
