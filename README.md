# cursor.nvim

A minimal Neovim port of Cursor's bundled Cursor Dark and Cursor Light themes.

The palettes are mapped from Cursor's bundled `cursor-dark-color-theme.json` and
`cursor-light-color-theme.json`, using their workbench `colors` and TextMate
`tokenColors`. Cursor's translucent editor colors are composited against the
corresponding editor background for Neovim.

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
